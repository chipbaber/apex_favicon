# Tutorial to Customize the Favicon for a APEX Application
Below you will find instruction on how to customize your favicon for an Oracle APEX application. Please reference this learning video for more details [https://youtu.be/NUBga8Gsb9Y](https://youtu.be/NUBga8Gsb9Y)

- These steps assume you have created a favicon set, typically this is done by a UI/UX artist. In our example you can reference images in the /fav folder for the example in this repo. In many cases you will have considerably more favicon sizes for various devices than in this example.

 ![](assets/README-8b552547.png)

- Open your APEX workspace and click into your application.

![](assets/README-4b8d65ba.png)

- Click on shared components.

![](assets/README-757bd404.png)

- Select static application files.

![](assets/README-69b31a1f.png)

- Select Upload File and upload your files. In this example we uploaded a .zip with a folder /fav.

![](assets/README-1a142c19.png)
![](assets/README-a63d0281.png)

- Navigate back to shared components

![](assets/README-8e1c361b.png)

- Drill into User Interface Attributes

![](assets/README-eb25222a.png)

- Select favicon

![](assets/README-84519499.png)


- Modify your HTML code and paste in. Below is an example of how to reference the favicons you uploaded to APEX earlier.

```
<link href="#APP_IMAGES#fav/favicon.ico" rel="shortcut icon">
<link href="#APP_IMAGES#fav/favicon-16x16.png" sizes="16x16 32x32" rel="icon">
<link href="#APP_IMAGES#fav/favicon-32x32.png" sizes="32x32" rel="icon">
<link href="#APP_IMAGES#fav/android-chrome-192x192.png" sizes="196x196" type="image/png" rel="icon">
<link href="#APP_IMAGES#fav/android-chrome-512x512.png" sizes="512x512" type="image/png" rel="icon">
<link href="#APP_IMAGES#fav/apple-touch-icon.png" sizes="180x180" rel="apple-touch-icon">
```

![](assets/README-937d214b.png)

- Run your application and view the icon.

![](assets/README-0c9372a6.png)
