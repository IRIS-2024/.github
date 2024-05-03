# 🚨 Introduction: MissingYou

![d5bfc93299dcfc9f](https://github.com/dsc-sookmyung/2024-IRIS-SolutionChallenge/assets/68546023/9a944c30-dfe8-4857-925f-cc4603671baf)

In September 2021, a system was introduced in Korea to send missing person notification text to citizens when high-risk individuals, such as children, teenagers, disabled people, and dementia patients, go missing. This messaging system has proven effective, significantly reducing the average time to find missing persons in high-risk groups from 34 hours to 3 hours and 10 minutes through the sightings of the citizens.

However, the process for transmission in this system is complex, involving passage through five organizations. Also, because they are text-based, missing person alert texts are easily forgotten by citizens and their use is limited by citizen fatigue.

Our team's app, "MissingYou", wants to help the reporter easily register a missing person report and ask as many people for help as soon as possible.

Leveraging the "Picture Superiority Effect," which suggests that visual information is easier to recognize and remember, the app is designed with a photo-oriented reporting system. The AI Image Generator can generate clothing images based on the provided information. Additionally, we provides location-based missing person reports and calculates the match rate between the sighting photos and the missing persons’ photos. Unlike one-way communication through existing systems, the app allows witnesses to check updates on the missing status through witness comments.

With "MissingYou", we want to expand beyond the existing high-risk missing persons ‘missing person notification text’ providing various types of missing reports and encouraging active sighting to involve everyone in creating a safe and peaceful community.
<br/>

## 🚩UN SDGs Goals & Target

<img src="https://github.com/dsc-sookmyung/2024-IRIS-SolutionChallenge/assets/76986589/7e8b417c-bbae-420b-9098-7047970d0d68" width="250"/><br/>
Goal 16: Peace, Justice and Strong Institutions
<br/>

## 🎥 Demo Video Link

[![3](https://github.com/dsc-sookmyung/2024-IRIS-SolutionChallenge/assets/68546023/1d48b4de-2ddd-465d-b98b-ac0a735da086)](https://youtu.be/MADOLeX1loE)

<br/>

## 🪄 How to run MissingYou

### Android

- Click [here](https://drive.google.com/drive/folders/1u7Qcz4GGhZxTVGQ8XDAntJ03MY6TW0gA?usp=sharing) to download an APK file.
- Install the "app-release.apk" file on your android device.

<br/>

## 🛠 Project Architecure

![image](https://github.com/dsc-sookmyung/2024-IRIS-SolutionChallenge/assets/68546023/b1b573ab-c66c-4d10-b0f1-6a86ead06c05)

<br/>

## 📱 App Screen

### 1. Login Page

<table style="border:none;">
   <tr>
      <td width="37%">
         <b>Page</b>
      </td>
      <td width="63%">
        <b>Explanation</b>
      </td>
   </tr>
   <tr>
      <td>
        <img src="https://github.com/IRIS-2024/Front/assets/76986589/63f66034-5db5-49f2-aeda-dfaae34216a6" width="250"/>                   
      </td>
      <td>
        Log in through Google login and use MissingYou.
      </td>
   </tr>
</table><br/>

### 2. Main Page

You can check the missing person reports around you.

<table style="border:none;">
   <tr>
      <td colspan='2' width="54%">
         <b>Page</b>
      </td>
      <td width="46%">
        <b>Explanation</b>
      </td>
   </tr>
       <td colspan='3'>
        <b>1) Latest Missing Person Reports Tab</b>
    </td>
   <tr>
      <td colspan='2'>
        <img src="https://github.com/IRIS-2024/Front/assets/76986589/556700ea-94e3-4a3f-88e8-dccb93ef5a86" width="250"/>
      </td>
      <td>
        Displays the missing person reports around you in the most up-to-date order.<br/>You can view brief missing person information and a photo, and click to view detailed of the report.
      </td>
   </tr>
    </tr>
        <td colspan='3'>
        <b>2) Map Tab</b>
        </td>
    <tr>
      <td>
        <img src="https://github.com/IRIS-2024/Front/assets/76986589/1c31b15c-df4d-4609-95ef-bda131576afc" width="250"/>
      </td>
      <td>
        <img src="https://github.com/IRIS-2024/Front/assets/76986589/b62e8d31-e261-4a03-b288-4ce0e7430a1a" width="250"/>
      <td>
       Displays the missing person reports around you as a marker on a map.<br/> Click the marker on the map to see the details of the report.
      </td>
   </tr>
</table><br/>

### 3. Report Registration Page

You can write a missing person report by clicking the 'Report' floating button on the main page.

<table style="border:none;">
   <tr>
      <td colspan='2' width="54%">
         <b>Page</b>
      </td>
      <td width="46%">
        <b>Explanation</b>
      </td>
   </tr>
   <tr>
      <td>
        <img src="https://github.com/IRIS-2024/Front/assets/76986589/ece16f40-681f-45ad-abba-4c5cff142e61" width="250"/> 
      </td>
      <td>
        <img src="https://github.com/IRIS-2024/Front/assets/76986589/3c2fb763-56de-4362-94cf-40b5a983a450" width="250"/>
      </td>
      <td>
        If there is a missing case, you can write a report. <br/><br/><br/> [Input Field] <br/> - photos(required*) <br/> - name (*) <br/> -gender (*), age (*) <br/> - height, weight <br/> - time of missing (*) <br/> - last location (*) <br/> - clothing at the time of missing (*) <br/> - special note
      </td>
   </tr>
      <tr>
      <td>
       <img src="https://github.com/IRIS-2024/Front/assets/76986589/cc1f022e-e096-4f76-b7bd-6f527b34f79d" width="250"/>
      </td>
      <td>
        <img src="https://github.com/IRIS-2024/Front/assets/76986589/15011169-7d39-488d-81e1-937e08af870c" width="250"/> 
      <td>
       (Left) The last location is entered via Google Maps. <br/><br/> (Right) When you press the registration button, an AI Image Generator creates an image of missing person’s clothing based on the provided information.
      </td>
   </tr>
</table><br/>

### 4. Report Page

You can check the details of the report and the witness comments on the report.

<table style="border:none;">
   <tr>
      <td colspan='2' width="54%">
         <b>Page</b>
      </td>
      <td width="46%">
        <b>Explanation</b>
      </td>
   </tr>
   <tr>
    <td colspan='3'>
        <b>1) Report Detail Tab</b>
    </td>
   </tr>
   <tr>
      <td colspan='2'>
         <img src="https://github.com/IRIS-2024/Front/assets/76986589/f7417507-222c-40b4-8720-a8c0b354932b" width="250"/>
      </td>
      <td>
         It shows the information and photos of the missing person written by the reporter.<br>The AI-generated image is shown with the guide 'This is an AI-generated image based on the information entered'.
      </td>
   </tr>
      <tr>
    <td colspan='3'>
        <b>2) Witness Comments Tab</b>
    </td>
   </tr>
   <tr>
      <td>
         <img src="https://github.com/IRIS-2024/Front/assets/76986589/12ab424a-cc0d-45ac-a4c2-6ad2d3a84e6b" width="250"/> 
      </td>
      <td>
        <img src="https://github.com/IRIS-2024/Front/assets/76986589/3da7922e-03f2-4b80-ae51-cf395f83019e" width="250"/>
      </td>
      <td>
         This page shows the witness comments along with the map. <br/><br/> Missing locations are marked with blue markers and witness comments are marked with red markers. <br/> Click a marker to display the corresponding witness comment at the top.
      </td>
   </tr>
      <tr>
      <td>
         <img src="https://github.com/IRIS-2024/Front/assets/76986589/e475b282-ca97-464a-80ff-16fae015976b" width="250"/> 
      </td>
      <td>
        <img src="https://github.com/IRIS-2024/Front/assets/76986589/192d9ca9-54dd-42f8-9b34-59f578a37188" width="250"/>
      </td>
      <td>
         The reporter can filter the comments based on the matching rate between the photos uploaded by the witness and those of the missing person.
      </td>
   </tr>
      <td>
        <img src="https://github.com/IRIS-2024/Front/assets/76986589/11978da3-aa4b-415a-9889-ed5e79fb23a5" width="250"/>
      </td>
      <td>
        <img src="https://github.com/IRIS-2024/Front/assets/76986589/5db30806-35cd-4804-a40a-02c6ba96ca41" width="250"/>
      </td>
      <td>
        (left) You can release a missing person report by clicking the 'Cancel Report' floating button.<br/><br/> (right) If you're not a reporter, you'll see a 'Submit a Comment' floating button. You can press this to write comment. Only the reporter and the Witness who submitted the comment can view the unblurred photos.
      </td>
   </tr>
</table><br/>

   </tr>
      <td>
      </td>
      <td>
      </td>
      <td>
      </td>
   </tr>

### 5. Witness Comment Submit Page

<table style="border:none;">
   <tr>
      <td colspan='2' width="54%">
         <b>Page</b>
      </td>
      <td width="46%">
        <b>Explanation</b>
      </td>
   </tr>
   <tr>
      <td>
         <img src="https://github.com/IRIS-2024/Front/assets/76986589/3f278d06-dd82-44d5-949b-ea0dbd44a5c5" width="250"/>
      </td>
      <td>
        <img src="https://github.com/IRIS-2024/Front/assets/76986589/fe78a18a-480d-4ba2-9960-c9d9d8c5068b" width="250"/> 
      </td>
      <td>
        If you spotted a missing person, you can write a witness comment. <br/><br/> [Input Field] <br/> - photos of witnessing (required*) <br/> - the time of witnessing (*) <br/> - the location of witnessing (*) <br/> - clothing at the time of witnessing <br/> - the situation at the time of the witnessing
      </td>
   </tr>
</table><br/>

### 6. My Page

<table style="border:none;">
   <tr>
      <td width="37%">
         <b>Page</b>
      </td>
      <td width="63%">
        <b>Explanation</b>
      </td>
   </tr>
   <tr>
      <td>
        <img src="https://github.com/IRIS-2024/Front/assets/76986589/8ed0dd27-4119-40f3-a9b7-778f36760ed2" width="250"/>                      
      </td>
      <td>
        You can view user information and app settings. <br/><br/> - User Infomation <br/><br/> - Post Management <br/> 1) Written missing person reports <br/> 2) Written witness comments <br/>3) bookmarked missing person reports <br/><br/> - App Settings <br/> Logout <br/> Sign out
      </td>
   </tr>
    <tr>
    <td colspan='3'>
        <b>1) Written missing person reports</b>
    </td>
   </tr>
   <tr>
    <td>
        <img src="https://github.com/IRIS-2024/Front/assets/76986589/481aee17-0584-4b33-8799-e580a6c7ed3c" width="250"/> 
    </td>
     <td>
        You can check and delete the missing person reports you have written.
    </td>
   </tr>
     <tr>
    <td colspan='3'>
        <b>2) Written witness comments</b>
    </td>
   </tr>
   <tr>
    <td>
        <img src="https://github.com/IRIS-2024/Front/assets/76986589/370c73c7-7347-4e50-96dc-2bc39d8afe65" width="250"/>
    </td>
     <td>
        You can check and delete the witness comments you have written.
    </td>
   </tr>
    <tr>
    <td colspan='3'>
        <b>3) bookmarked missing person reports</b>
    </td>
   </tr>
   <tr>
    <td>
        <img src="https://github.com/IRIS-2024/Front/assets/76986589/0e76efb3-4674-41a6-a4e1-bebc862731d8" width="250"/>
    </td>
     <td>
        You can check the bookmarked missing person reports.
    </td>
   </tr>
</table><br/>

### 7. Notification Setting (Android only)

<table style="border:none;">
   <tr>
      <td colspan='2' width="54%">
         <b>Page</b>
      </td>
      <td width="46%">
        <b>Explanation</b>
      </td>
   </tr>
      <tr>
      <td>
         <img src="https://github.com/IRIS-2024/Front/assets/76986589/939c36fb-e8b6-4aef-8a94-f663eb2705a4" width="250"/>
      </td>
      <td>
        <img src="https://github.com/IRIS-2024/Front/assets/76986589/3c281b46-b173-49d2-bc31-0fb3e2c32da7" width="250"/> 
      </td>
      <td>
        You can select your region of interest from My Page. When a new missing person report is submitted in your region of interest, a notification is sent.
      </td>
   </tr>
   <tr>
      <td>
         <img src="https://github.com/IRIS-2024/Front/assets/76986589/221d4bbc-30f1-4ff3-a081-1a1447643710" width="250"/>
      </td>
      <td>
        <img src="https://github.com/IRIS-2024/Front/assets/76986589/4d6a364e-cf4e-4ab9-a972-721c5f60b166" width="250"/> 
      </td>
      <td>
        - Notification received.<br/><br/>
        * A notification is sent when a new comment is posted on the missing person report You wrote.<br/>
      </td>
   </tr>
</table><br/>

### 8. Multilingual Support

<table style="border:none;">
   <tr>
      <td colspan='2' width="54%">
         <b>Page</b>
      </td>
      <td width="46%">
        <b>Explanation</b>
      </td>
   </tr>
      <tr>
      <td>
         <img src="https://github.com/IRIS-2024/Front/assets/76986589/5ea7de9e-bff2-4970-8ba0-c21ed795b09b" width="250"/>
      </td>
      <td>
        <img src="https://github.com/IRIS-2024/Front/assets/76986589/556700ea-94e3-4a3f-88e8-dccb93ef5a86" width="250"/> 
      </td>
      <td>
        (left) Korean, (right) English<br/>
        We offer support in both English and Korean to broaden accessibility.
      </td>
   </tr>
</table><br/>

## 👯‍♀️ People of IRIS

<table style="border:none;">
   <tr>
      <td width="7%">
         <b>Name</b>
      </td>
      <td width="22%">
        <a href="https://github.com/hap6v6"><b>김희서</b></a> <br/>(Heeseo Kim)
      </td>
      <td width="22%">
        <a href="https://github.com/lizuAg"><b>이주은</b></a> <br/>(Jueun Lee)
      </td>
      <td width="22%">
             <a href="https://github.com/2hyerin"><b>이혜린</b></a> <br/>(Hyerin Lee)
      </td>
      <td width="22%">
             <a href="https://github.com/YenaChoi00"><b>최예나</b></a> <br/>(Yena Choi)
      </td>
   </tr>
    <tr>
      <td>
         Role
      </td>
      <td>
       - UI Design (Main Page, Report Registration Page, Witness Comment Submit Page)<br/>- Implement Google Map API (Google Map Widget, Geocoding)<br/>- Implement API Communication: Main Page, Report Registration Page, Witness Comment Submit Page, My Page, Bookmark)<br/>
      </td>
        <td>
        - Deploy spring server with GCP Virtual Machine<br/>- Manage MySql DB with GCP SQL<br/>- Server APIs
      </td>
        <td>
- Deploy FastAPI with GCP virtual machine<br/>- Calculate similarity between faces<br/>- Generate clothing image<br/>- Train models to face detection and verification
      </td>
               <td>
- UI Design (Report Detail Page, Report Comment Page, My Page, Login Page)<br/>- Implement Google Map API (Google Map Widget)<br/>- Implement Google Login<br/>
      </td>
   </tr>
<tr>
      <td>
         GitHub<br/>Repository
      </td>
      <td>
      <a href="https://github.com/hap6v6"><img src="https://avatars.githubusercontent.com/u/76986589?v=4" width="150"></a> 
      </td>
        <td>
          <a href="https://github.com/lizuAg"><img src="https://github.com/lizuAg.png" width="150"></a> 
      </td>
        <td>
<a href="https://github.com/2hyerin"><img src="https://github.com/dsc-sookmyung/2024-IRIS-SolutionChallenge/assets/88357058/e24a0b1d-232f-474e-8135-f14fcb9397ea" width="150"></a> 
      </td>
        <td>
<a href="https://github.com/YenaChoi00"><img src="https://avatars.githubusercontent.com/u/71956482?v=4" width="150"></a> 
      </td>
   </tr>
</table><br/>
