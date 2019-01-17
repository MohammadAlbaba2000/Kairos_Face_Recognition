
<img align="right" src="https://github.com/ishaanjav/Kairos_Face_Recognition/blob/master/Identification.gif" width="315">

# Kairos_Face_Recognition

**The purpose of this Android app is to use Kairos's SDK for Android in order to implement facial recognition. Kairos's API offers one of the simplest methods to integrate such features into any Android app.** 

Features of this app include: 
- **Registering users** given their image and name.
- **Identifying users** when given their image.

You can view more about the features of Kairos's API [on their website](https://www.kairos.com/features). They used to have a GitHub repository with their Android SDK where it contained information about using Kairos in Android, however it seems like they removed that repository. You can find the equivalent information below.

<br/>
<br/>
<br/>

-----

<img align="left" src="https://github.com/ishaanjav/Kairos_Face_Recognition/blob/master/Full%20Process.gif" width="311">

## Usage

**Please note that in order to use this app, you MUST get the API Key and App ID from the [Kairos API Dashboard](https://developer.kairos.com/admin). In the Setup section, you will find the steps on how to request a free trial of the API and use it in the app**.


The app consists of two buttons, an `EditText` and an `ImageView`. The two buttons are used for the **enrollment and recognition processes** by taking a picture of a person. That picture is then displayed in an `ImageView`.
- **Enrollment Process:** The `EditText` is used to enter the name of the person being enrolled. The `Enroll` button is then used to launch the camera and register the person with their name along with the image of their face.
- **Identification Process:** The `Identify` button is used to launch the camera and identify the person in the image. It uses the Kairos API to output the result of the person with the closest matching face. If it can't identify the person, then it returns an empty `String`.

<br/>
<br/>
<br/>

-----
## Setup
The steps below cover how to get the API Key from Kairos through a free trial and then use the key in the app in order for it to function as expected.
### Downloading to Android Studio
To use the app, you can clone it from this GitHub repository as a zip file, extract the contents of the file, and open it as a project in Android Studio. Once you have done so, it can be run on your Android device.
### Getting the Kairos free trial
Unless you already have a Kairos pricing plan that you are paying for, you will have to create an account on [Kairos's Website](https://github.com/ishaanjav/Kairos_Face_Recognition/edit/master/README.md) which can be [done here](https://github.com/ishaanjav/Kairos_Face_Recognition/edit/master/README.md). The page should look similar to the image below:

<img align="center" src="https://github.com/ishaanjav/Kairos_Face_Recognition/blob/master/Kairos%20Free%20Trial.PNG" width="900">

To get the free trial, you will have to fill in the required fields to create your account after which you will have to confirm the account through the email that you have provided. **The email that you provide must be a *non-disposable* email, meaning that it cannot end in something like `@gmail.com`.** 

### Getting the API Key and App ID
Upon getting the free trial, you can log into Kairos's website at [this link](https://developer.kairos.com/login). You can then access the [API Dashboard](https://developer.kairos.com/admin) at [this link](https://developer.kairos.com/admin) and copy the API Key and App ID which will be used in the app in the following step. You should see something similar to the image below.

<img align="center" src="https://github.com/ishaanjav/Kairos_Face_Recognition/blob/master/API%20Dashboard.PNG" width="900">

###### **Please note that if you are using the free trial, you will only receive one API Key and one App ID. What this means is that since you are on a free trial, you will only be able to use the Kairos API in one app. For [Kairos's Pricing Plans](https://www.kairos.com/pricing), you can check out [this link](https://www.kairos.com/pricing) which has plans starting at $99 per month and $0.02 per transaction. *Custom plans are available upon request.*** 

