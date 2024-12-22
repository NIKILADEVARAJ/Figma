# Ex09 Event Registration Web Application
## Date:22/12/2024

## AIM:
To design, develop and deploy a web application for event registration.

## DESIGN STEPS:

### Step 1:
Create a new frame.

### Step 2:
Select any one preset size of your choice.

### Step 3:
Select the shapes you need.

### Step 4:
Import images as needed.

### Step 5:
Create pages based on your need and link them.

### Step 6:

Validate the HTML and CSS code.

### Step 6:

Publish the website in the given URL.

## DESIGN TOOL:
Figma

## CODE:
```
Home page 
HTML 
 
<div class="container--0-">
  <svg
    width="291"
    height="118"
    viewBox="0 0 291 118"
    fill="none"
    xmlns="http://www.w3.org/2000/svg"
  >
    <g filter="url(#filter0_i_610_18)">
      <rect x="1" y="1" width="289" height="116" fill="#10C1B2"></rect>
    </g>
    <rect x="0.5" y="0.5" width="290" height="117" stroke="black"></rect>
    <defs>
      <filter
        id="filter0_i_610_18"
        x="0"
        y="0"
        width="291"
        height="122"
        filterUnits="userSpaceOnUse"
        color-interpolation-filters="sRGB"
      >
        <feFlood flood-opacity="0" result="BackgroundImageFix"></feFlood>
        <feBlend
          mode="normal"
          in="SourceGraphic"
          in2="BackgroundImageFix"
          result="shape"
        ></feBlend>
        <feColorMatrix
          in="SourceAlpha"
          type="matrix"
          values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"
          result="hardAlpha"
        ></feColorMatrix>
        <feOffset dy="4"></feOffset>
        <feGaussianBlur stdDeviation="2"></feGaussianBlur>
        <feComposite
          in2="hardAlpha"
          operator="arithmetic"
          k2="-1"
          k3="1"
        ></feComposite>
        <feColorMatrix
          type="matrix"
          values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0.25 0"
        ></feColorMatrix>
        <feBlend
          mode="normal"
          in2="shape"
          result="effect1_innerShadow_610_18"
        ></feBlend>
      </filter>
    </defs>
  </svg>
  <div class="text-0-1-3">REGISTER</div>
  <svg
    width="291"
    height="102"
    viewBox="0 0 291 102"
    fill="none"
    xmlns="http://www.w3.org/2000/svg"
  >
    <g filter="url(#filter0_i_610_21)">
      <rect x="1" y="1" width="289" height="100" fill="#07D2BE"></rect>
    </g>
    <rect x="0.5" y="0.5" width="290" height="101" stroke="black"></rect>
    <defs>
      <filter
        id="filter0_i_610_21"
        x="0"
        y="0"
        width="291"
        height="106"
        filterUnits="userSpaceOnUse"
        color-interpolation-filters="sRGB"
      >
        <feFlood flood-opacity="0" result="BackgroundImageFix"></feFlood>
        <feBlend
          mode="normal"
          in="SourceGraphic"
          in2="BackgroundImageFix"
          result="shape"
        ></feBlend>
        <feColorMatrix
          in="SourceAlpha"
          type="matrix"
          values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"
          result="hardAlpha"
        ></feColorMatrix>
        <feOffset dy="4"></feOffset>
        <feGaussianBlur stdDeviation="2"></feGaussianBlur>
        <feComposite
          in2="hardAlpha"
          operator="arithmetic"
          k2="-1"
          k3="1"
        ></feComposite>
        <feColorMatrix
          type="matrix"
          values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0.25 0"
        ></feColorMatrix>
        <feBlend
          mode="normal"
          in2="shape"
          result="effect1_innerShadow_610_21"
        ></feBlend>
      </filter>
    </defs>
  </svg>
  <div class="text-0-1-5">LOGIN</div>
  <div class="text-0-1-6">MUSIC EVENT</div>
</div>

CSS
.container--0- {
  position: absolute;
  left: -2124px;
  top: -435px;
  width: 412px;
  height: 917px;
  background-color: #ffffff;
  justify-content: start;
  align-items: start;
}
.text-0-1-3 {
  width: 236px;
  height: 58px;
  color: #000000;
  font-size: 48px;
  font-family: Inter, "Bold";
  font-weight: 700;
  text-align: left;
  vertical-align: top;
}
.text-0-1-5 {
  width: 149px;
  height: 58px;
  color: #000000;
  font-size: 48px;
  font-family: Inter, "Bold";
  font-weight: 700;
  text-align: left;
  vertical-align: top;
}
.text-0-1-6 {
  width: 327px;
  height: 104px;
  color: #000000;
  font-size: 40px;
  font-family: Inter, "Extra Bold";
  font-weight: 800;
  text-align: left;
  vertical-align: top;
}

EVENT 
HTML
<div class="container--0-">
<div class="text-0-1-1">Sound Shakedown<br /></div>
  <div class="text-0-1-2">Music Mosaic<br /></div>
  <svg
    width="46"
    height="40"
    viewBox="0 0 46 40"
    fill="none"
    xmlns="http://www.w3.org/2000/svg"
  >
    <path
      d="M23 0L28.3883 15.2016H45.8254L31.7185 24.5967L37.1068 39.7984L23 30.4033L8.89315 39.7984L14.2815 24.5967L0.174644 15.2016H17.6117L23 0Z"
      fill="black"
    ></path></svg
  ><svg
    width="46"
    height="40"
    viewBox="0 0 46 40"
    fill="none"
    xmlns="http://www.w3.org/2000/svg"
  >
    <path
      d="M23 0L28.3883 15.2016H45.8254L31.7185 24.5967L37.1068 39.7984L23 30.4033L8.89315 39.7984L14.2815 24.5967L0.174644 15.2016H17.6117L23 0Z"
      fill="black"
    ></path>
  </svg>
  <div class="text-0-1-5">MUSIC EVENTS</div>
  <div class="text-0-1-6">MUSIC EVENTS</div>
  <svg
    width="46"
    height="40"
    viewBox="0 0 46 40"
    fill="none"
    xmlns="http://www.w3.org/2000/svg"
  >
    <path
      d="M23 0L28.3883 15.2016H45.8254L31.7185 24.5967L37.1068 39.7984L23 30.4033L8.89315 39.7984L14.2815 24.5967L0.174644 15.2016H17.6117L23 0Z"
      fill="black"
    ></path></svg
  ><svg
    width="46"
    height="40"
    viewBox="0 0 46 40"
    fill="none"
    xmlns="http://www.w3.org/2000/svg"
  >
    <path
      d="M23 0L28.3883 15.2016H45.8254L31.7185 24.5967L37.1068 39.7984L23 30.4033L8.89315 39.7984L14.2815 24.5967L0.174644 15.2016H17.6117L23 0Z"
      fill="black"
    ></path></svg
  ><svg
    width="46"
    height="40"
    viewBox="0 0 46 40"
    fill="none"
    xmlns="http://www.w3.org/2000/svg"
  >
    <path
      d="M23 0L28.3883 15.2016H45.8254L31.7185 24.5967L37.1068 39.7984L23 30.4033L8.89315 39.7984L14.2815 24.5967L0.174644 15.2016H17.6117L23 0Z"
      fill="black"
    ></path></svg
  ><svg
    width="46"
    height="40"
    viewBox="0 0 46 40"
    fill="none"
    xmlns="http://www.w3.org/2000/svg"
  >
    <path
      d="M23 0L28.3883 15.2016H45.8254L31.7185 24.5967L37.1068 39.7984L23 30.4033L8.89315 39.7984L14.2815 24.5967L0.174644 15.2016H17.6117L23 0Z"
      fill="black"
    ></path></svg
  ><svg
    width="46"
    height="40"
    viewBox="0 0 46 40"
    fill="none"
    xmlns="http://www.w3.org/2000/svg"
  >
    <path
      d="M23 0L28.3883 15.2016H45.8254L31.7185 24.5967L37.1068 39.7984L23 30.4033L8.89315 39.7984L14.2815 24.5967L0.174644 15.2016H17.6117L23 0Z"
      fill="black"
    ></path>
  </svg>
  <div class="text-0-1-12">Rhythm and Dreams</div>
  <div class="text-0-1-13">Melody Junction<br /></div>
  <div class="text-0-1-14">Vibe Tribe Gathering<br /></div>
  <div class="text-0-1-15">Frequency Fest<br /></div>
  <div class="text-0-1-16">Voices of Nature<br /></div>
</div>
CSS
.container--0- {
  position: absolute;
  left: -1581px;
  top: -298px;
  width: 412px;
  height: 917px;
  background-color: #ffffff;
  justify-content: start;
  align-items: start;
}
.text-0-1-1 {
  width: 282px;
  height: 78px;
  color: #ffffff;
  font-size: 32px;
  font-family: Inter, "Regular";
  font-weight: 400;
  text-align: left;
  vertical-align: top;
}
.text-0-1-2 {
  width: 207px;
  height: 78px;
  color: #ffffff;
  font-size: 32px;
  font-family: Inter, "Regular";
  font-weight: 400;
  text-align: left;
  vertical-align: top;
}
.text-0-1-5 {
  width: 306px;
  height: 48px;
  color: #ffffff;
  font-size: 40px;
  font-family: Inter, "Extra Bold";
  font-weight: 800;
  text-align: left;
  vertical-align: top;
}
.text-0-1-6 {
  width: 344px;
  height: 53px;
  color: #991414;
  font-size: 40px;
  font-family: Inter, "Extra Bold";
  font-weight: 800;
  text-align: left;
  vertical-align: top;
}
.text-0-1-12 {
  width: 306px;
  height: 39px;
  color: #ffffff;
  font-size: 32px;
  font-family: Inter, "Regular";
  font-weight: 400;
  text-align: left;
  vertical-align: top;
}
.text-0-1-13 {
  width: 281px;
  height: 44px;
  color: #ffffff;
  font-size: 32px;
  font-family: Inter, "Regular";
  font-weight: 400;
  text-align: left;
  vertical-align: top;
}
.text-0-1-14 {
  width: 312px;
  height: 78px;
  color: #ffffff;
  font-size: 32px;
  font-family: Inter, "Regular";
  font-weight: 400;
  text-align: left;
  vertical-align: top;
}
.text-0-1-15 {
  width: 234px;
  height: 78px;
  color: #ffffff;
  font-size: 32px;
  font-family: Inter, "Regular";
  font-weight: 400;
  text-align: left;
  vertical-align: top;
}
.text-0-1-16 {
  width: 251px;
  height: 78px;
  color: #ffffff;
  font-size: 32px;
  font-family: Inter, "Regular";
  font-weight: 400;
  text-align: left;
  vertical-align: top;
}


REGISTER
HTML
<div class="container--0-">
 <div class="text-0-1-1">EVENT REGISTRATION FORM</div>
  <div class="text-0-1-2">Fill the form</div>
  <svg
    width="298"
    height="53"
    viewBox="0 0 298 53"
    fill="none"
    xmlns="http://www.w3.org/2000/svg"
  >
    <rect width="298" height="53" fill="white"></rect></svg
  ><svg
    width="241"
    height="51"
    viewBox="0 0 241 51"
    fill="none"
    xmlns="http://www.w3.org/2000/svg"
  >
    <rect width="241" height="51" fill="white"></rect></svg
  ><svg
    width="241"
    height="51"
    viewBox="0 0 241 51"
    fill="none"
    xmlns="http://www.w3.org/2000/svg"
  >
    <rect width="241" height="51" fill="white"></rect>
  </svg>
  <div class="text-0-1-6">Gender</div>
  <svg
    width="241"
    height="51"
    viewBox="0 0 241 51"
    fill="none"
    xmlns="http://www.w3.org/2000/svg"
  >
    <rect width="241" height="51" fill="white"></rect>
  </svg>
  <div class="text-0-1-9">Age</div>
  <svg
    width="310"
    height="47"
    viewBox="0 0 310 47"
    fill="none"
    xmlns="http://www.w3.org/2000/svg"
  >
    <rect width="310" height="47" fill="white"></rect>
  </svg>
  <div class="text-0-1-11">Register Number</div>
  <svg
    width="242"
    height="42"
    viewBox="0 0 242 42"
    fill="none"
    xmlns="http://www.w3.org/2000/svg"
  >
    <rect width="242" height="42" fill="white"></rect>
  </svg>
  <div class="text-0-1-13">Department</div>
  <div class="text-0-1-14">Full Name</div>
  <svg
    width="277"
    height="47"
    viewBox="0 0 277 47"
    fill="none"
    xmlns="http://www.w3.org/2000/svg"
  >
    <rect width="277" height="47" fill="white"></rect>
  </svg>
  <div class="text-0-1-17">Mobile Number</div>
  <svg
    width="292"
    height="50"
    viewBox="0 0 292 50"
    fill="none"
    xmlns="http://www.w3.org/2000/svg"
  >
    <rect width="292" height="50" fill="white"></rect>
  </svg>
  <div class="text-0-1-19">Email ID</div>
  <svg
    width="291"
    height="42"
    viewBox="0 0 291 42"
    fill="none"
    xmlns="http://www.w3.org/2000/svg"
  >
    <rect width="291" height="42" fill="white"></rect>
  </svg>
  <div class="text-0-1-21">Event To Register</div>
  <svg
    width="249"
    height="82"
    viewBox="0 0 249 82"
    fill="none"
    xmlns="http://www.w3.org/2000/svg"
  >
    <g filter="url(#filter0_i_611_83)">
      <rect width="249" height="82" fill="#64042B"></rect>
    </g>
    <rect x="0.5" y="0.5" width="248" height="81" stroke="black"></rect>
    <defs>
      <filter
        id="filter0_i_611_83"
        x="0"
        y="0"
        width="249"
        height="86"
        filterUnits="userSpaceOnUse"
        color-interpolation-filters="sRGB"
      >
        <feFlood flood-opacity="0" result="BackgroundImageFix"></feFlood>
        <feBlend
          mode="normal"
          in="SourceGraphic"
          in2="BackgroundImageFix"
          result="shape"
        ></feBlend>
        <feColorMatrix
          in="SourceAlpha"
          type="matrix"
          values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"
          result="hardAlpha"
        ></feColorMatrix>
        <feOffset dy="4"></feOffset>
        <feGaussianBlur stdDeviation="2"></feGaussianBlur>
        <feComposite
          in2="hardAlpha"
          operator="arithmetic"
          k2="-1"
          k3="1"
        ></feComposite>
        <feColorMatrix
          type="matrix"
          values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0.25 0"
        ></feColorMatrix>
        <feBlend
          mode="normal"
          in2="shape"
          result="effect1_innerShadow_611_83"
        ></feBlend>
      </filter>
    </defs>
  </svg>
  <div class="text-0-1-23">REGISTER</div>
</div>
CSS
.container--0- {
  position: absolute;
  left: -1059px;
  top: -184px;
  width: 464px;
  height: 924px;
  background-color: #ffffff;
  justify-content: start;
  align-items: start;
}
.text-0-1-1 {
  width: 339px;
  height: 29px;
  color: #23b473;
  font-size: 24px;
  font-family: Inter, "Semi Bold";
  font-weight: 600;
  text-align: left;
  vertical-align: top;
}
.text-0-1-2 {
  width: 138px;
  height: 29px;
  color: #ffffff;
  font-size: 24px;
  font-family: Inter, "Semi Bold";
  font-weight: 600;
  text-align: left;
  vertical-align: top;
}
.text-0-1-6 {
  width: 86px;
  height: 29px;
  color: #000000;
  font-size: 24px;
  font-family: Inter, "Semi Bold";
  font-weight: 600;
  text-align: left;
  vertical-align: top;
}
.text-0-1-9 {
  width: 47px;
  height: 29px;
  color: #000000;
  font-size: 24px;
  font-family: Inter, "Semi Bold";
  font-weight: 600;
  text-align: left;
  vertical-align: top;
}
.text-0-1-11 {
  width: 196px;
  height: 29px;
  color: #000000;
  font-size: 24px;
  font-family: Inter, "Semi Bold";
  font-weight: 600;
  text-align: left;
  vertical-align: top;
}
.text-0-1-13 {
  width: 140px;
  height: 29px;
  color: #000000;
  font-size: 24px;
  font-family: Inter, "Semi Bold";
  font-weight: 600;
  text-align: left;
  vertical-align: top;
}
.text-0-1-14 {
  width: 114px;
  height: 29px;
  color: #000000;
  font-size: 24px;
  font-family: Inter, "Semi Bold";
  font-weight: 600;
  text-align: left;
  vertical-align: top;
}
.text-0-1-17 {
  width: 177px;
  height: 29px;
  color: #000000;
  font-size: 24px;
  font-family: Inter, "Semi Bold";
  font-weight: 600;
  text-align: left;
  vertical-align: top;
}
.text-0-1-19 {
  width: 93px;
  height: 29px;
  color: #000000;
  font-size: 24px;
  font-family: Inter, "Semi Bold";
  font-weight: 600;
  text-align: left;
  vertical-align: top;
}
.text-0-1-21 {
  width: 204px;
  height: 29px;
  color: #000000;
  font-size: 24px;
  font-family: Inter, "Semi Bold";
  font-weight: 600;
  text-align: left;
  vertical-align: top;
}
.text-0-1-23 {
  width: 236px;
  height: 58px;
  color: #ffffff;
  font-size: 48px;
  font-family: Inter, "Bold";
  font-weight: 700;
  text-align: left;
  vertical-align: top;
}

THANK YOU 
HTML
<div class="container--0-">
<div class="text-0-1-2">THANK YOU!</div>
  <div class="text-0-1-3">
    Thank you so much for taking the time to attend our event. Your presence
    made it even more special, and we’re grateful for your support.
  </div>
  <div class="text-0-1-4">CONTACT US</div>
  <div class="text-0-1-5">Email <br />saveetha@gmail.com</div>
  <div class="text-0-1-6">Phone <br />9934567890<br />9876543210</div>
</div>
CSS
.container--0- {
  position: absolute;
  left: -477px;
  top: -79px;
  width: 412px;
  height: 917px;
  background-color: #ffffff;
  justify-content: start;
  align-items: start;
}
.text-0-1-2 {
  width: 266px;
  height: 72px;
  color: #000000;
  font-size: 40px;
  font-family: Inter, "Bold";
  font-weight: 700;
  text-align: left;
  vertical-align: top;
}
.text-0-1-3 {
  width: 351px;
  height: 156px;
  color: #000000;
  font-size: 15px;
  font-family: Inter, "Regular";
  font-weight: 400;
  text-align: left;
  vertical-align: top;
}
.text-0-1-4 {
  width: 298px;
  height: 28px;
  color: #1c8313;
  font-size: 32px;
  font-family: Inter, "Extra Bold Italic";
  font-weight: 800;
  text-align: left;
  vertical-align: top;
}
.text-0-1-5 {
  width: 346px;
  height: 78px;
  color: #f20911;
  font-size: 32px;
  font-family: Inter, "Extra Bold Italic";
  font-weight: 800;
  text-align: left;
  vertical-align: top;
}
.text-0-1-6 {
  width: 403px;
  height: 133px;
  color: #f50e0e;
  font-size: 32px;
  font-family: Inter, "Extra Bold Italic";
  font-weight: 800;
  text-align: left;
  vertical-align: top;
}   
```

## OUTPUT:
![alt text](<Screenshot (128).png>)
![alt text](<Screenshot (129).png>)
![alt text](<Screenshot (130).png>)
![alt text](<Screenshot (131).png>)

## RESULT:
The program to design, develop and deploy a web application for event registration is completed successfully.
