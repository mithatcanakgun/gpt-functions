## GPT Function Calling Multi Model Playground

This is an experimental project using OpenAI function calling and Replicate to provide multi model content generation.

Instead of using separate interfaces for image generation, video generation, audio generation, and general text natural language processing, this app combines them all together into a single prompt.

Feautures currently supported:

-   Text to image
-   Text to video
-   Text to audio
-   General natural language processing

Examples of what you might ask:

-   Create a 4 day travel itinerary for Amsterdam
-   Create an image of someone in their production studio creating beats, futuristic, dim lighting, bronx new york
-   Create a track embodying The Weeknd’s style, mixing emotive melodies, atmospheric sounds, and intricate beats with innovative synths and reverberant effects.
-   Create a video of clown fish swimming in a coral reef, beautiful, 8k, perfect, award winning, national geographic

## Prerequisites

To run this app, you must have the following:

1. OpenAI API Key
2. Replicate token

## Running the app

To run this app, follow these steps:

1. Clone the repo

```sh
git clone git@github.com:mithatcanakgun/gpt-functions.git
```

2. Change into the directory and install the dependencies:

```sh
cd gpt-functions
npm install
```

3. Set environment variables in a file named `.env.local` (you can copy `.env.local.example`)

```
OPENAI_API_KEY=
REPLICATE_TOKEN=
```

4. Run the app

```sh
npm run dev
```
