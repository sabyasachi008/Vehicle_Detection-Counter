# Vehicle Counter

This script is designed to count the number of vehicles in a video. It uses OpenCV to process the video and detect vehicles.

## Dependencies

- OpenCV

## Algorithm

The script uses the following algorithm to detect vehicles:

1. Read the video frame by frame.
2. Convert the frame to grayscale.
3. Apply Gaussian blur to reduce noise.
4. Apply background subtraction to extract the foreground.
5. Dilate the foreground to fill in any holes.
6. Find contours in the dilated foreground.
7. Filter the contours to remove any that are not likely to be vehicles.
8. Draw a rectangle around each valid contour.
9. Draw a line to indicate the counting line.
10. Count the number of vehicles that pass the counting line.

## Usage

1. Make sure you have OpenCV installed.
2. Run the script with the following command:


## Configuration

The script has a few configuration parameters that you can adjust:

- `min_width_react`: The minimum width of a rectangle to be considered a vehicle.
- `min_height_react`: The minimum height of a rectangle to be considered a vehicle.
- `count_line_position`: The y-coordinate of the line that separates the counting area.

You can adjust these parameters by modifying the corresponding variables in the script.

## Benefits
<li>Traffic Control & Congestion Control.
<li>Easy to use for Traffic Management/Planning.
<LI>Parking Management System.

## Contributions
Contributions are welcome! We value your input and encourage you to actively participate in the project. If you have any ideas, suggestions, bug reports, or feature requests, please don't hesitate to open an issue on GitHub. Additionally, we appreciate any code contributions you may have. If you'd like to contribute code, please submit a pull request, and we will review it as soon as possible. Thank you for your support!

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Author   
[Sabyasachi Ghosh](https://github.com/sabyasachi008)

## Contact
<li>Email ID: sabyasachighosh008@gmail.com
<li>GitHub: https://github.com/sabyasachi008
<li>Phone No: 7501539881    