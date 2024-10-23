# FFmpeg SRT Caller

## Introduction

Simple Docker container that acts as SRT caller to test an SRT connection

## How to use it

- Download the docker-compose.yaml file to your computer
- Download the .env file to the same folder where you have placed the .yaml file
- Download a sample .mp4 video file to the same folder and name it 'video.mp4'
- Edit the .env file to set the correct information about the SRT listener
- Launch the container with the following command:

 ```bash
 docker compose up
 ```

 - Check if the video feed is received by the listener

 