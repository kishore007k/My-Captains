# My-Captains😎

## This is a Project Repository for My Captains

![Project's Actual Image](https://user-images.githubusercontent.com/34863222/89726646-51968a00-da3a-11ea-8755-5a0cbdd596b2.PNG)

---

### Sources📚

>Use the code snippet⛓ below to send mail using a captcha

```html
<form action="https://formspree.io/usermail@gmail.com" method="POST">
```

>For the Map🗺 I used an Google API

#### This is My Google Maps API you can get your own by the steps given below

```html
<iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d972.0337219145268!2d80.21373820953015!3d12.963219329845975!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x3a525dbe61ae540f%3A0x938689daad97ba01!2sArumugam%20St%2C%20Ram%20Nagar%20South%2C%20Madipakkam%2C%20Chennai%2C%20Tamil%20Nadu%20600042!5e0!3m2!1sen!2sin!4v1594472620871!5m2!1sen!2sin" width="100%" height="100%" frameborder="0" style="border:0;" allowfullscreen="" aria-hidden="false" tabindex="0"></iframe>
```

#### Steps to Get your own Google API

1.Go to the [Google Cloud Platform](https://console.cloud.google.com/google/maps-apis/new?project=portfolio-283012&folder=&organizationId=) Console.

2.Click the project drop-down and select or create the project for which you want to add an API key.

3.Click the menu button  and select APIs & Services > Credentials.

4.On the Credentials page, click Create credentials > API key.

5.The API key created dialog displays your newly created API key.

6.Click Close.

7.The new API key is listed on the Credentials page under API keys. (Remember to [restrict the API](https://developers.google.com/maps/documentation/javascript/get-api-key#restrict_key) key before using it in production.)

### Add the API key to your request

<p>You must include an API key with every Maps JavaScript API request. In the following example, replace YOUR_API_KEY with your API key.</p>

```html
<script async defer src="https://maps.googleapis.com/maps/api/js?key=YOUR_API_KEY&callback=initMap" type="text/javascript"></script>
```

### Reference🔖

[Google API](https://developers.google.com/maps/documentation/javascript/get-api-key)
