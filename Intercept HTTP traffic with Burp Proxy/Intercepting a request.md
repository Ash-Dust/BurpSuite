Burp Suite allows us to Intercept between the browser and the server to get to know how the website behave when the browser doing different actions.

## Step 1: Launch Burp's browser
![image](https://github.com/Ash-Dust/BurpSuite/assets/120457430/cd0cbcb6-10cf-45ae-b58b-c8809c9fac38)

Go to Proxy > Intercept. Turn on the Intercept and click Open Browser to Launch Burp's browser

![image](https://github.com/Ash-Dust/BurpSuite/assets/120457430/8a8d0689-91f8-4546-ba18-1ed60d5224ed)
We can adjust the Window to see both Burp Suite and browser at the same time.

## Step 2: Intercept a request
We can try to go to a website, in this case: https://portswigger.net.
We can see that the browser doesn't load because Burp Suite has intercepted the request to the server.

![image](https://github.com/Ash-Dust/BurpSuite/assets/120457430/3573a316-31d3-4189-b2c7-932e507a713f)

On the left side we can see the request of the browser trying to connect with the website. Here, we can can study it, and even modify it, before forwarding it to the target server.

## Step 3: Forward the request
Click the forward button several times to send the requests to the server until the browser load in the page

## Step 4: Switch off interception
Click the Intercept is on button so that it now says Intercept is off.

![image](https://github.com/Ash-Dust/BurpSuite/assets/120457430/6b6348c4-8d97-40a2-90cc-92e857ee3868)

Once Intercept is off we can get back to the browser to check that it is working as usual.

![image](https://github.com/Ash-Dust/BurpSuite/assets/120457430/7272e7e8-cc0a-450d-925f-071af3a3f6d9)

## 5: View the HTTP history

Go to the Proxy > HTTP history tab. Here, you can see the history of all HTTP traffic that has passed through Burp Proxy, even while interception was switched off.

Click on any entry in the history to view the raw HTTP request, along with the corresponding response from the server.

![image](https://github.com/Ash-Dust/BurpSuite/assets/120457430/0af7aa91-e620-4317-a57d-e9b4c68cc9cb)

This lets us explore the website as normal and study the interactions between Burp's browser and the server afterward, which is more convenient in many cases.
