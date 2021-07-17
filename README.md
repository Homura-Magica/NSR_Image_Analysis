# Image Analysis Data Description

## Work Range

Jiangxin He's Part: From folder "2020_01_06" to folder "2020_02_07".

## Release Notes

1. Unnecessary pixel count columns 4-12 are removed.

2. Horizon/Vertical column is now added. H stands for Horizon and V stands for Vertical.

3. Date of Image column: data is now printed according to folders' name.

4. Pixels per unit data after folder "2021_01_16" will be calculated by Microsoft Excel. Only pixel count data will be manually copied to Microsoft Excel sheet.

## Error Correction

1. Pixel count raw data is directly copied & pasted from Fiji > Analyze > Set Scale… > Distance in pixels by shortcuts, thus error rate should be very low.

2. Pixels per unit data for folders before "2021_01_16" is manually copied from Fiji > Analyze > Set Scale… > Scale, typo error may exist. Thankfully this issue can be easily solved though calculated in Microsoft Excel.

3. Draw line error. Because in many image, there is no reference line, or dots thus it is difficult to draw exactly the same line. I personally recommend that next time, reference parallel lines or reference dots can be built in number tags.

## Some Concerns and Suggestions

1. Small sample rate: each image is only drawn three lines to record pixel counts.  

2. Standard deviation is recommended to track how precision the raw data is.

3. In many cases, images do not have obvious locating point that helps to draw a parallel line.

4. Lens distortion, that may present, can cause line should be curved instead of straight.

5. labels with grid may be helpful for computer to analyze.

6. Another methods is that simply stick a paper of grid on the top of culture medium. 
