# Expo ImagePicker Video URI Issue

This repository demonstrates a common issue when using Expo's ImagePicker to select videos. The selected video's URI is not compatible with the standard React Native `Image` component, leading to unexpected behavior.

## Problem

The `Image` component in React Native expects an image URI. When a video is selected using `ImagePicker`, it returns a URI that doesn't work with `Image`, resulting in a blank or broken image display.

## Solution

The solution involves using a video player component like `Video` from `react-native-video` to display the selected video.