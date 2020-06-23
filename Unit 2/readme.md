# Unit 2: Video Instruments
### Outcome:
    Media curating part 1. What types of video are best suited for different applications & techniques? 
### Exercise:
    - Students are provided with 3 different video processing apps and 4 - 6 different video samples
    - Video samples from cameras, film, games, and television.
    - Should contain a mix of jump cutting, stable backgrounds, b&w vs. color, saturation and exposure levels
    - Students should try out each video sample with each video app.
    - Students then describe in 1-2 paragraphs per application which samples worked best and worst as input.
    - Include qualitative rationale as to why a sample is ranked a certain way.

### Given Application(s):
    - 3 applications
        - presence / background subtraction which highlights foreground
        - Motion / edge-detection
        - Recolor / color-mapping
    - require as minimal computer spec as possible to run.
    - Similar to week 1, should function largely as black boxes with minimal surface UI






### Test Notes:
(From Andrew)
- if "foregrounder" had another slider to control blend it could help students understand better key concepts of this unit, allows them to experiment with how process of input effects output.
- In "Recolorer" it might be helpful for students to make connection about modulation of input to output if it showed the colors in the recolor color pallettes. 
- In "Hue Shifter" maybe change the number box to a slider also. If student has never touched max before they wont know how to finely change float values, slider more intutively suggests testing wide range of different values. 
- Might want to add into the description about motion edges that the technique is known as optical flow.
- Particle patches weren't working for me at first cause of issues with cv.jit. I reinstalled the package and then they worked but ran really really slow on my computer.
- "Stutter Frame" is pretty confusing to me. Window is black or barely visable and changing parameters doesn't seem to make much of a difference. If students have to hit reset output every time after changing parameters then changing the parameters should send a bang to the reset.
- For all the patches might be easier to have a umenu or something similar already loaded with pre-given media files but also lets them easily add there own in as well. (I made the sc.dropmedia patch to do this)
- For all patches it would be easier to navigate if all the jit.world objects were set to @floating 1.
- For all patches only having playback volume slide is kinda misleading from the modulation of media concept. Having volume be the only modulator parameter in most of the patches leaves me unsatisfied and desiring for more because I can't effect the output of the video which is suppose to be the focus of the unit. I would suggest maybe moving the volume slider and resolution output textbutton off to the side and make them smaller so students can still change these parameters but understand that doing that isn't the modulation of media that your asking them to experiment with.
