# Final project of the Android Developer Nanodegree

## Simple CFD
Simple CFD is an app to learn computational fluid dynamics (CFD). The document *simple_cfd_project_proposal.pdf* contains further details. Note that this is only a prototype app.

<<<<<<< HEAD
<style type='text/css'>
  .column {
    float: left;
    width: 25%;
    padding: 5px;
  }
  .row::after {
    content: "";
    clear: both;
    display: table;
  }
</style>

<div class="row">
 <div class="column" >
   <img src="screenshots/main_view.png" alt="Topics overview" style="width:100%">
 </div>
 <div class="column">
   <img src="screenshots/course_view.png" alt="Lecture overview" style="width:100%">
 </div>
 <div class="column">
   <img src="screenshots/lecture_read_view.png" alt="Reading lecture" style="width:100%">
 </div>
 <div class="column">
   <img src="screenshots/lecture_video_view.png" alt="Video lecture" style="width:100%">
 </div>
</div>
=======
<img src="screenshots/main_view.png" width="150">
<img src="screenshots/course_view.png" width="150">
<img src="screenshots/lecture_read_view.png" width="150">
<img src="screenshots/lecture_video_view.png" width="150">
>>>>>>> ec8b939316c30d37083ad61a18e352b1cac817c8

## Files and folders
* \*.png: course topic header images; the images are loaded by the app from the github repository.
* lecture_html.html: lorum ipsm lecture to test the app
* topics_list.json: topic information to create topic objects stored in JSON format; contains, for example, links to images and lectures.
* SimpleCFD: Android Studio project folder; contains the actual app.

## Google service
<<<<<<< HEAD
The app uses Google's [AdMob](https://developers.google.com/admob/android/quick-start) to display advertisement at each start of the app and [Firebase Analytics](https://firebase.google.com/docs/analytics/android/start/) to track the popularity of topics. To use the services you need valid API-keys for the Android Youtube Player (see link below), AdMob, and Firebase. The keys are stored in the *SimpleCFD/gradle.properties* file (AdMob, Youtube) and in the *SimpleCFD/app/google-services.json* file (Firebase).
=======
The app uses google's AdMob to display advertisement at each start of the app and Firebase Analytics to track the popularity of topics.
>>>>>>> ec8b939316c30d37083ad61a18e352b1cac817c8

## Software and libraries
Build with
* Android Studio 3.1
* JRE 1.8.0
<<<<<<< HEAD
* [Android Youtube Player API 1.2.2](https://developers.google.com/youtube/android/player/)
* [Picasso (load and display images)](http://square.github.io/picasso/)
* [Butterknife (Binding views easily)](http://jakewharton.github.io/butterknife/)
=======
* Android Youtube Player API 1.2.2
>>>>>>> ec8b939316c30d37083ad61a18e352b1cac817c8

## License
MIT License

<<<<<<< HEAD
Copyright (c) 2018 Andre Weiner
=======
Copyright (c) [2018] [Andre Weiner]
>>>>>>> ec8b939316c30d37083ad61a18e352b1cac817c8

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
