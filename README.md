# Ex08 Event Registration Web Application
## Date:20.03.2026

## AIM:
To design, develop and deploy a web application for event registration using Figma UI tool.

## UI DESIGN TOOL:
Figma

## DESIGN STEPS:

### Step 1:
Use frames to represent screens or sections.

### Step 2:
Add column grids for consistent spacing and alignment.

### Step 3:
Insert shapes, text, buttons, and icons.

### Step 4:
Use Auto Layout for flexible, responsive design.

### Step 5:
Define color, text, and effect styles globally for consistency.

### Step 6:
Name layers logically and group related elements.

### Step 6:
Link frames to show navigation or interactions.

### Step 7:
Select the specific frame while generating code using Anima plugin.

## CODE:
```
Home page:1

import officialHomepagePlayNowOnIosAndroid1 from "./official-homepage-play-now-on-ios-android-1.png";

export const Iphone = (): JSX.Element => {
  return (
    <div className="bg-[#730c80] w-full min-w-[393px] min-h-[852px] relative">
      <img
        className="absolute top-0 left-0 w-[393px] h-[852px] aspect-[0.59] object-cover"
        alt="Official homepage"
        src={officialHomepagePlayNowOnIosAndroid1}
      />

      <div className="absolute top-[713px] left-[52px] w-[5px] h-[3px] bg-[#d9d9d9]" />

      <div className="absolute top-[777px] left-[78px] w-[261px] h-[51px] bg-[#420af8] blur-[2px]" />

      <div className="absolute top-[778px] left-[126px] w-[227px] [font-family:'Glegoo-Regular',Helvetica] font-normal text-white text-2xl tracking-[0] leading-[normal] whitespace-nowrap">
        Loading..50%
      </div>
    </div>
  );
};

page:2

import download131 from "./download-13-1.png";
import rectangle3 from "./rectangle-3.svg";

export const IphonePlus = (): JSX.Element => {
  return (
    <div className="bg-white w-full min-w-96 min-h-[852px] relative">
      <img
        className="absolute top-0 left-0 w-96 h-[852px] aspect-[0.45] object-cover"
        alt="Download"
        src={download131}
      />

      <img
        className="absolute top-[598px] left-[53px] w-60 h-16"
        alt="Rectangle"
        src={rectangle3}
      />

      <div className="absolute top-[609px] left-[95px] w-[194px] [font-family:'Glegoo-Regular',Helvetica] font-normal text-black text-2xl tracking-[0] leading-[normal]">
        Tap to play
      </div>

      <div className="absolute top-[754px] left-6 w-[149px] h-[71px] bg-[#12f20b33] backdrop-blur-[2.0px] backdrop-brightness-[100.0%] backdrop-saturate-[100.0%] [-webkit-backdrop-filter:blur(2.0px)_brightness(100.0%)_saturate(100.0%)] shadow-[inset_0_1px_0_rgba(255,255,255,0.40),inset_1px_0_0_rgba(255,255,255,0.32),inset_0_-1px_1px_rgba(0,0,0,0.13),inset_-1px_0_1px_rgba(0,0,0,0.11)]" />

      <div className="absolute top-[767px] left-[35px] w-[157px] [font-family:'Glegoo-Regular',Helvetica] font-normal text-[#ea12aa] text-2xl tracking-[0] leading-[normal]">
        Characters
      </div>

      <div className="absolute top-[754px] left-48 w-[171px] h-[71px] bg-[#fe08e133] backdrop-blur-[2.0px] backdrop-brightness-[100.0%] backdrop-saturate-[100.0%] [-webkit-backdrop-filter:blur(2.0px)_brightness(100.0%)_saturate(100.0%)] shadow-[inset_0_1px_0_rgba(255,255,255,0.40),inset_1px_0_0_rgba(255,255,255,0.32),inset_0_-1px_1px_rgba(0,0,0,0.13),inset_-1px_0_1px_rgba(0,0,0,0.11)]" />

      <div className="absolute top-[747px] left-[227px] w-[136px] [font-family:'Glegoo-Regular',Helvetica] font-normal text-[#fa4d08] text-2xl tracking-[0] leading-[normal]">
        Claim Rewards
      </div>
    </div>
  );
};

page:3

import x2331 from "./233-1.png";
import textOnAPath from "./text-on-a-path.svg";

export const IphonePlus = (): JSX.Element => {
  return (
    <div className="bg-white overflow-hidden w-full min-w-[383px] min-h-[852px] relative">
      <img
        className="absolute top-0 left-0 w-[383px] h-[852px] aspect-[0.75] object-cover"
        alt="Element"
        src={x2331}
      />

      <img
        className="absolute top-[395px] left-[-582px] w-[291px] h-[109px]"
        alt="Text on a path"
        src={textOnAPath}
      />

      <div className="absolute top-[312px] left-[66px] w-[303px] h-[91px] bg-[#372b7e33] backdrop-blur-[2.0px] backdrop-brightness-[100.0%] backdrop-saturate-[100.0%] [-webkit-backdrop-filter:blur(2.0px)_brightness(100.0%)_saturate(100.0%)] shadow-[inset_0_1px_0_rgba(255,255,255,0.40),inset_1px_0_0_rgba(255,255,255,0.32),inset_0_-1px_1px_rgba(0,0,0,0.13),inset_-1px_0_1px_rgba(0,0,0,0.11)]" />

      <p className="absolute top-[319px] left-[94px] w-[260px] [font-family:'Glegoo-Regular',Helvetica] font-normal text-[#21d87f] text-2xl tracking-[0] leading-[normal]">
        Use one key to play retry
      </p>
    </div>
  );
};

page:4

import x2331 from "./233-1.png";
import textOnAPath from "./text-on-a-path.svg";

export const IphonePlus = (): JSX.Element => {
  return (
    <div className="bg-white overflow-hidden w-full min-w-[383px] min-h-[852px] relative">
      <img
        className="absolute top-0 left-0 w-[383px] h-[852px] aspect-[0.75] object-cover"
        alt="Element"
        src={x2331}
      />

      <img
        className="absolute top-[395px] left-[-582px] w-[291px] h-[109px]"
        alt="Text on a path"
        src={textOnAPath}
      />

      <div className="absolute top-[312px] left-[66px] w-[303px] h-[91px] bg-[#372b7e33] backdrop-blur-[2.0px] backdrop-brightness-[100.0%] backdrop-saturate-[100.0%] [-webkit-backdrop-filter:blur(2.0px)_brightness(100.0%)_saturate(100.0%)] shadow-[inset_0_1px_0_rgba(255,255,255,0.40),inset_1px_0_0_rgba(255,255,255,0.32),inset_0_-1px_1px_rgba(0,0,0,0.13),inset_-1px_0_1px_rgba(0,0,0,0.11)]" />

      <p className="absolute top-[319px] left-[94px] w-[260px] [font-family:'Glegoo-Regular',Helvetica] font-normal text-[#21d87f] text-2xl tracking-[0] leading-[normal]">
        Use one key to play retry
      </p>

      <div className="absolute top-[78px] left-0 w-[383px] h-[58px] bg-[#d6bfbf]" />

      <div className="absolute top-[87px] left-[38px] w-[331px] [font-family:'Glegoo-Regular',Helvetica] font-normal text-black text-2xl tracking-[0] leading-[normal]">
        M.Hari prasath-25018172
      </div>
    </div>
  );
};

```


## OUTPUT:
![alt text](<Screenshot (33).png>) 
![alt text](<Screenshot (30).png>)
 ![alt text](<Screenshot (31).png>)
  ![alt text](<Screenshot (32).png>)


## RESULT:
The program to design, develop and deploy a web application for event registration using Figma UI tool is completed successfully.
