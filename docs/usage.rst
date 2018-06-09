=====
Usage
=====

To use Django User Images in a project, add it to your `INSTALLED_APPS`:

.. code-block:: python

    INSTALLED_APPS = (
        ...
        'django_user_images.apps.DjangoUserImagesConfig',
        ...
    )

Add Django User Images's URL patterns:

.. code-block:: python

    from django_user_images import urls as django_user_images_urls


    urlpatterns = [
        ...
        url(r'^', include(django_user_images_urls)),
        ...
    ]
