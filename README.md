# If you only want to test out backend to receive picture (express)

-just nodemon start the express-server folder and you can do your submission on the frontend or postman

-test especailly the POST route http://localhost:3000/base64

-you can add the input as shown below in Postman

![input](https://user-images.githubusercontent.com/58338071/185515143-23f9bc10-09b2-4471-8f05-65a4cbe0bde8.JPG)

-after you submit and it respond back with "connected", double check your server folder. There should be a new cat image.

# How to run the code?

## Start the Front End (Not really / It's literally just a single html page)

Go to the directory under src/html and double click open the "index.html" file.

## Start the back end (Assuming you have node js epxerience)

Go to the directory under express-server. Then, use terminal type

```
npm i
```

to install all the necessary dependencies

To start the server at local host 3000: 
```
npm start
```
## Testing

Go to the opened index.html page and open up debugg console on your browser

Click ```choose files``` button to find a single picture. On the console it would display ```Ready to Submit```
and then click ```submit```

The console would display some basic information about the file you just attached and on the website's Data portion, you would see some info as well.

After you submit go to directory under express/server, refresh your folder

There should be a new file or photo named "picture" or whatever name it's called, but the point is, you just submitted a photo by yourself and revieced it!

## Reference:

Guide:

https://formcarry.com/blog/how-to-upload-files-as-base64/



