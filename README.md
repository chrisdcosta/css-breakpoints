# CSS Breakpoints

Might be useful for someone who has to carry out manual tuning of CSS. This list and screen dimensions are courtesy of the Brave Browser at the date of this commit. It also helps when deciding which of the devices to focus on since the list in Brave is quite large.

## How I used it

1) I started the set up of CSS as if it was desktop as responsive as possible. 

2) Then I focussed on adjusting the CSS from "Pixel 3 XL" width screen.
  
3) Next I made minor changes to the smallest screen "JioPhone 2"
   
4) Then moved all working CSS up through the media queries (broad "types" of device identified by the "breakpoint" column) to find the largest width that they sensibly worked at.

```css
@media only screen and (max-width: 1280px) {}
@media only screen and (max-width: 1024px) {}
@media only screen and (max-width: 768px) {}
@media only screen and (max-width: 540px) {}
@media only screen and (max-width: 430px) {}
@media only screen and (max-width: 414px) {}
@media only screen and (max-width: 393px) {}
@media only screen and (max-width: 360px) {}
@media only screen and (max-width: 240px) {}
```

| CSS Testing           | Width | Height | Type          | Breakpoint |
|-----------------------|-------|--------|---------------|------------|
| JioPhone 2            | 240   | 320    | Mini Phone    | here       |
| Galaxy Fold           | 280   | 653    | Mini Phone    |            |
| Galaxy S9+            | 320   | 658    | Phone         |            |
| iPhone 4              | 320   | 480    | Phone         |            |
| iPhone 5/SE           | 320   | 568    | Phone         |            |
| Nokia Lumia 520       | 320   | 533    | Phone         |            |
| Pixel 4               | 353   | 745    | Phone         |            |
| Blackberry Z30        | 360   | 640    | Phone         |            |
| Galaxy S5             | 360   | 640    | Phone         | here       |
| Galaxy S8+            | 360   | 740    | Phone         |            |
| Galaxy SIII           | 360   | 640    | Phone         |            |
| Microsoft Lumia 950   | 360   | 640    | Phone         |            |
| Moto G4               | 360   | 640    | Phone         |            |
| Nexus 5               | 360   | 640    | Phone         |            |
| iPhone 6/7/8          | 375   | 667    | Phone         |            |
| iPhone SE             | 375   | 667    | Phone         |            |
| iPhone XR             | 375   | 812    | Phone         |            |
| LG Optimus L70        | 384   | 640    | Phone         |            |
| Nexus 4               | 384   | 640    | Phone         |            |
| iPhone 12 Pro         | 390   | 844    | Phone         |            |
| Pixel 3               | 393   | 786    | Phone         |            |
| Pixel 3 XL            | 393   | 786    | Phone         | here       |
| Pixel 2               | 411   | 731    | Large Phone   |            |
| Pixel 2 XL            | 411   | 823    | Large Phone   |            |
| Facebook on Android   | 412   | 892    | Large Phone   |            |
| Galaxy A51/71         | 412   | 914    | Large Phone   |            |
| Galaxy S20 Ultra      | 412   | 915    | Large Phone   |            |
| Moto G Power          | 412   | 823    | Large Phone   |            |
| Nexus 5X              | 412   | 732    | Large Phone   |            |
| Nexus 6               | 412   | 732    | Large Phone   |            |
| Nexus 6P              | 412   | 732    | Large Phone   |            |
| Pixel 7               | 412   | 915    | Large Phone   |            |
| iPhone 6/7/8 Plus     | 414   | 736    | Large Phone   | here       |
| iPhone XR             | 414   | 896    | Large Phone   |            |
| iPhone 14 Pro Max     | 430   | 932    | Large Phone   | here       |
| Nokia N9              | 480   | 854    | Large Phone   |            |
| Surface Duo           | 540   | 720    | Large Phone   | here       |
| Blackberry Playbook   | 600   | 1024   | Tablet        |            |
| Nexus 7               | 600   | 960    | Tablet        | here       |
| Microsoft Lumia 550   | 640   | 360    | Tablet        |            |
| Galaxy Tab S4         | 712   | 1138   | Tablet        |            |
| iPad                  | 768   | 1024   | Tablet        | here       |
| iPad Mini             | 768   | 1024   | Tablet        |            |
| Kindle Fire HDX       | 800   | 1280   | Desktop       |            |
| Nexus 10              | 800   | 1280   | Desktop       |            |
| iPad Air              | 820   | 1180   | Desktop       |            |
| Surface Pro 7         | 912   | 1368   | Desktop       |            |
| IPad Pro              | 1024  | 1366   | Desktop       | here       |
| IPad Pro              | 1024  | 1366   | Desktop       |            |
| Nest Hub              | 1024  | 600    | Desktop       |            |
| Nest Hub Max          | 1280  | 800    | Large Desktop | here       |
| Responsive            |       |        |               |            |

