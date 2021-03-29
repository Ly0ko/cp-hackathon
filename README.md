# cp-hackathon

My entry for the Twitch Channel Points Hackathon

# Getting Started

Required environment variables:

- `TWITCH_CLIENT_ID`
- `TWITCH_CLIENT_SECRET`
- `TWITCH_BROADCASTER_ID`
- `WH_CALLBACK_URL`
- `WH_SECRET`

If running locally, it's recommended to use a tool like Ngrok to create an https tunnel for the webhook callback URL.

## Running

Donwload dependencies

`go mod download`

Run

`go mod run main.go`

There is also a simple `Dockerfile` included if you'd like to use Docker.

## hydrate.ino

The `hydrate.ino` file contains the code for the ESP32 microcontroller.
