---
layout: default
---

Text can be **bold**, _italic_, or ~~strikethrough~~.

[Link to another page](./another-page.html).

There should be whitespace between paragraphs.

There should be whitespace between paragraphs. We recommend including a README, or a file with information about your project.

------------------------------------------------------------------------------------------

## Project 1: Gray Level Transformed Directional Normalized Standard Deviations (NSTD) for Edge Detection

**Link: https://github.com/sinhapm/GravMagGreyTransDirectionEdge.git**

**Scope of Program Field: Gravity, Magnetic & Remote Sensing Dataset**

_**Platform: MATLAB**_

_**Program File name : start_LineamentGreyLevelsNSTD.m**_

The program calculates the Gray Level Transformed Directional Normalized Standard Deviations (NSTD) for Edge Detection.

It takes the 2D gridded points input (Irap Classic Points format) such as Input File Format (X(Integer) Y(Integer) Z(Float)) - XY in ascending order top to bottom direction of Input data: 1. West to East: Left to Right, 2. South to North: Top to Bottom

**Sample output image (zoomed)**

![](./assets/img/Image_GravLineament.jpg)

Open source Free Air Gravity data downloaded from the following site: https://topex.ucsd.edu/cgi-bin/get_data.cgi

------------------------------------------------------------------------------------------

## Phase-Decomposition-3D-Seismic-Data-Odd-Even-Function-Method
**Matlab Program to perform the 3D seismic data Phase Decomposition based on Odd-Even function. It computes only the odd components (-90 degree, 90 degree) and the even components (+/-180 degree, 0 degree) from the 3D seismic data**.

**Scope of Program Field: Attribute Analysis - 3D Seismic Phase Decomposition**

_**Platform: MATLAB(R2020), Opendtect 6.4**_

**Program file**: "**Test_run_codes_pdoed3D_sample_3Dseismic_matfile.m**" provided script reads the sample seismic input data ("**sample_3Dseismic.mat**") and calls the phase decomposition function scripts except two files (**od_doprocess.m** & **od_getparameters.m**) and display a Inline results (./reference\images\Sample3Dseismic). User can change the input parameters values and display the result.

For Opendtect Volume Builder: Except "Test_run_codes_pdoed3D_sample_3Dseismic_matfile.m" files, all other MATLAB ".m" required to be complied via MATLAB C Compiler to generate the c shared dll file.

Sample data ("**sample_3Dseismic.mat**") outputs test: script: "Test_run_codes_pdoed3D_sample_3Dseismic_matfile.m"

![](./assets/img//image_phasedecomposition.jpg)

------------------------------------------------------------------------------------------

### Header 3

```js
// Javascript code with syntax highlighting.
var fun = function lang(l) {
  dateformat.i18n = require('./lang/' + l)
  return true;
}
```

```ruby
# Ruby code with syntax highlighting
GitHubPages::Dependencies.gems.each do |gem, version|
  s.add_dependency(gem, "= #{version}")
end
```

#### Header 4

*   This is an unordered list following a header.
*   This is an unordered list following a header.
*   This is an unordered list following a header.

##### Header 5

1.  This is an ordered list following a header.
2.  This is an ordered list following a header.
3.  This is an ordered list following a header.

###### Header 6

| head1        | head two          | three |
|:-------------|:------------------|:------|
| ok           | good swedish fish | nice  |
| out of stock | good and plenty   | nice  |
| ok           | good `oreos`      | hmm   |
| ok           | good `zoute` drop | yumm  |

### There's a horizontal rule below this.

* * *

### Here is an unordered list:

*   Item foo
*   Item bar
*   Item baz
*   Item zip

### And an ordered list:

1.  Item one
1.  Item two
1.  Item three
1.  Item four

### And a nested list:

- level 1 item
  - level 2 item
  - level 2 item
    - level 3 item
    - level 3 item
- level 1 item
  - level 2 item
  - level 2 item
  - level 2 item
- level 1 item
  - level 2 item
  - level 2 item
- level 1 item

### Small image

![Octocat](https://github.githubassets.com/images/icons/emoji/octocat.png)

### Large image

![Branching](https://guides.github.com/activities/hello-world/branching.png)


### Definition lists can be used with HTML syntax.

<dl>
<dt>Name</dt>
<dd>Godzilla</dd>
<dt>Born</dt>
<dd>1952</dd>
<dt>Birthplace</dt>
<dd>Japan</dd>
<dt>Color</dt>
<dd>Green</dd>
</dl>

```
Long, single-line code blocks should not wrap. They should horizontally scroll if they are too long. This line should be long enough to demonstrate this.
```

```
The final element.
```
