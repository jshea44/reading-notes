# Readings: Audio, Video, Images
This reading helps us understand how to input audio and video into our webpage. It also helps us understand a different way of laying out a webpage with the use of grid. In combination with displaying a webpage, we also learn how to make images responsive and why it's important especially with different sized devices. 
## Video and Audio Content
  1. Instead of using technologies like Flash and Silverlight, which had security risks as well as accessibility issues, we can now control the HTML elements `<video>` and `<audio>`using the Javascript API. 
  2. 1. `src` - This contains the path to your video file.
     2. `controls` - This adds a control interface from the browser. You can also build one from the Javascript API, but it must be able to start/stop and adjust the volume at a minimun.
  3. It's important to have fallback content incase the user's browser doesn't support the video that is trying to be displayed. A different video can be used that older browsers can access, or perhaps a link to the original video.
  4. Video and Audio used to be solo performers. Video danced, and Audio sang. Both were great in their own right, but one day they decided to perform together as a duo. They are now bigger than they could ever have been solo. 

## A Complete Guide To Grid
  1. Grid is a lot more concise than flex. Flex is also one dimensional while grid is two dimensional. 
  2. 1. Grid container - This is the parent of all the grid items. It's what `display: grid` is on. 
     2. Grid item - These are the children to the grid container.
     3. Grid line - These are the lines that divide the grid, either row lines or column lines.

## Responsive Images
  1. A reason developers would make images responsive would be for the device that the image may be viewed on. You don't need a high resolution image on a mobile device.
  2. 1. `srcset` - This contains a list of images and their intrinsic sizes that the browser can choose from.
     2. `sizes` -  This indicates what image to choose from the `srcset` based on the size of the device.
  3. `srcset` is better because of the intrinsic nature of how webpages are loaded. Images are loaded first in the page with HTML before CSS or Javascript is read.


## Things I want to know more about
