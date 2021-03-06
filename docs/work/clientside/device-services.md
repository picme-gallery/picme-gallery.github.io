The client component will need access to:
* Device Services
    1. [Native Camera App](https://developer.android.com/training/camera/photobasics)
        > This service will be used by PicMe Gallery to allow our users to upload photos directly from within our app, without having to switch back to the native camera app.
        This service is for convenience. If the service is interrupted, then the users will still be able to upload a photo by taking a picture, and then uploading it from their gallery (i.e. Google Photos, etc.) to PicMe Gallery.
    2. [App Data and Files](https://developer.android.com/guide/topics/data)
        > This service will be used by our app to complete the file-sharing portion of PicMe Gallery's features. It will allow users to save files on their phone.
        Simultaneously, this service will also allow users to share files (photos) to the galleries (events) that are hosted on the server or Web.
        If access to App Data and Files, or more specifically, the shared-storage and file-sharing that is a part of App Data and Files is interrupted, it will effectively render our app useless.
                                                                                
