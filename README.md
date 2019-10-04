# My Online Classroom

Online Classroom developed in HTML5 and CSS3.

![alt screenshot](https://raw.githubusercontent.com/lrusso/ClassRoom/master/ClassRoom.png)


## Web

https://lrusso.github.io/ClassRoom/ClassRoom.htm

## Video demo

https://www.youtube.com/watch?v=WNGvmvJ_Q60

## How to create your own classes

In https://github.com/lrusso/ClassRoom/blob/master/ClassRoom_Class01.htm, you will see this two variables:

```
var timeEvents = [1,7,17,24,28];
var classAudio = "ClassRoom_Class01.mp3";
```

The timeEvents is an array that sets how many seconds must pass for the next transition.

The classAudio is the path to MP3 audio file that has the voice of the teacher of the class.

## Handling transitions

```
<table>
     <tr>
          <td colspan="2"><span class="classroom_resource classroom_resource_hidden">Introduction</span></td>
     </tr>
     <tr>
          <td><img alt="" class="classroom_resource classroom_resource_hidden" src="data:image/png;base64,iVBOR=="></td>
          <td><img alt="" class="classroom_resource classroom_resource_hidden" src="data:image/png;base64,iVBOR=="></td>
     <tr>
          <td><img alt="" class="classroom_resource classroom_resource_hidden" src="data:image/png;base64,iVBOR=="></td>
          <td><img alt="" class="classroom_resource classroom_resource_hidden" src="data:image/png;base64,iVBOR=="></td>
     </tr>
</table>
```
