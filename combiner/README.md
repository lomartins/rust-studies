# Image Combiner
A program that combine two images into one.

The program use [image library](https://github.com/image-rs/image) to read two image files and combine into one output.

## Running:
```shell
cargo run -- first_image_path second_image_path output_path
```

## Result
Running the following command:
```shell
cargo run -- ./images/stonks.jpg ./images/not-stonks.jpg ./images/confused-stonks.jpg
```
- ### Image 1
![image 1](images/stonks.jpg)
- ### Image 2
![image 2](images/not-stonks.jpg)

- ### Output
![output](images/output.jpg)