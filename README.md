# Indian Currency Denomination Detection

This project proposes a system that uses image processing techniques to detect the denomination of Indian currency notes. The system takes an image of the note as input and displays the amount of the note.

## How it Works

The system uses ORB (Oriented FAST and Rotated BRIEF) to extract key points and descriptors from the input image. These features are then matched against a set of training data using a brute force matcher. If a match is found, the system displays the image of the note along with the amount present in the currency.

## Data

The testing data is provided in the `DSIPData` repository, and can be accessed by cloning the repository using the following command:

```
!git clone https://github.com/PradyotC/DSIPData/
```

The training data is also provided in the repository, and consists of images of Indian currency notes with different denominations.

## Usage

To run the system, you can use the provided code in the repository. Make sure to have all the necessary libraries installed before running the code. The code takes an input image and matches it against the training data to detect the denomination of the note.