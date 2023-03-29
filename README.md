# ComputerVisionClass CS473 Spring 2023
Here are ways that we made computers see!

Homework 2 - Here we have some transforms applied to some images.

We have defined a function that takes in a matrix and does some transform on an image.

Homework 3 - Inside of HW_3/out_im/ are the images that were created by the program. Here are the panorama images:


Step 1: Get the first image to be expanded as such

![im1_expanded](https://user-images.githubusercontent.com/67016155/226788645-13fcaf7a-1345-496f-bb64-00a7236adb9e.jpg)

Step 2: Apply the transform to the second image

![im2_transformed](https://user-images.githubusercontent.com/67016155/226788685-c8c0d2a5-4e9b-4ee7-a0a6-f3f7ee67a02f.jpg)

Step 3: Apply blend

![im1_blend](https://user-images.githubusercontent.com/67016155/226788775-94e52cf7-0151-42cd-86b5-1caba5aec31a.png)
![im2_blend](https://user-images.githubusercontent.com/67016155/226788800-d4241e5d-eff5-4483-9bb5-173ae82c4d18.png)

Step 4: Add together (most excellently)

![panorama_set1](https://user-images.githubusercontent.com/67016155/226788574-de2636c8-f098-4e09-824d-82e870c0694d.jpg)

![panorama_set1](https://user-images.githubusercontent.com/67016155/226788549-638b1ca1-9d8b-48e9-b879-a7402e460d7e.jpg)

![panorama_set1](https://user-images.githubusercontent.com/67016155/226788526-6be40f2d-62c7-4f39-b9ac-5acb18eb4b79.jpg)


The way that the panorama works is we first find the keypoints and descriptors for each image. Then we match the keypoints and descriptors between the two images. Then we find the homography between the two images. We apply the homography to the second image. Then we stitch the images together using a blending ramp.
