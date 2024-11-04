# LoFi_Steampunk
HackNJIT 2024

## About the Project

### Inspiration
The idea for LoFi Steampunk came from a fascination with the lo-fi music genre, known for its relaxing, downtempo beats, and the unique, retro-futuristic aesthetic of steampunk. We wanted to create a project that combined these two concepts—an interactive platform that lets users generate and listen to lo-fi beats while being immersed in a steampunk-inspired environment. By pairing audio and visuals, we attempted to create an experience that’s both soothing and visually captivating.

### What it does
LoFi Steampunk is a web application that generates random lo-fi chord progressions, providing users with an evolving soundscape of relaxing beats. The app allows users to:
- Generate unique chord progressions.
- Play, stop, and loop through beats.
- Experience a dynamic background that changes with each chord progression, creating a steampunk visual theme.

The result is an application that feels like an ad-free lo-fi music generator with a visual through a steampunk-inspired background.

### How we built it
LoFi Steampunk was built using:
- **React** for the front-end framework, allowing us to create an interactive user interface with reusable components.
- **Tone.js** for handling the audio synthesis and sequencing, enabling us to create and control sounds directly in the browser.
- **standardized-audio-context** to ensure cross-browser compatibility for Web Audio API functions.
- **CSS** for styling and creating the steampunk-themed visuals, using custom images and animations to make the interface feel reactive.
- **GitHub Pages** to deploy the project, making it accessible to users directly from the GitHub repository.

Throughout the coding process, we focused on creating and integrating audio with a little visual that felt cohesive and intentional. Each chord progression changes triggers a background change, immersing users further into the steampunk theme.

### Challenges we ran into
- **Audio Synchronization**: Ensuring that the generated chords and beats played in sync required fine-tuning, especially when dealing with randomized chord progressions.
- **Cross-Browser Compatibility**: The Web Audio API behaves differently across browsers, which required additional configuration with `standardized-audio-context` to maintain consistency.
- **Visual and Audio Integration**: Creating a seamless experience where visual changes matched audio changes were more challenging than anticipated. We had to find the right balance between interactive elements and aesthetic appeal.
- **GitHub Pages Deployment**: Hosting a React project with dynamic assets on GitHub Pages presented some hurdles, especially with paths for static assets and routing within a subdirectory.

### Accomplishments that we're proud of
- **Combining Audio and Visual Elements**: We’re proud of how we managed to blend the audio and visuals to create an immersive lo-fi and steampunk experience. The dynamic background that changes with each chord adds an extra layer of engagement.
- **Interactive Music Generation**: Successfully using Tone.js to generate unique chord progressions and rhythms in real-time was a significant accomplishment.
- **Responsive Design**: Making the app responsive and accessible on both desktop and mobile devices ensures a broader reach for our audience.
- **Deploying to GitHub Pages**: Deploying a full-fledged React project to GitHub Pages allowed us to share our project with the world, making it accessible with just a URL.

### What we learned
- **Web Audio API and Tone.js**: This project helped us understand the Web Audio API and introduced us to the capabilities of Tone.js, especially for real-time music generation.
- **React Component Structure**: Building this project helped us improve our skills in React, particularly in structuring and managing components for interactive, state-driven applications.
- **Cross-Browser Compatibility**: Ensuring compatibility across browsers taught us how to handle inconsistencies, especially when working with web audio and complex visual layouts.
- **Deployment Challenges**: We learned the nuances of deploying React applications on GitHub Pages, including handling paths and optimizing asset loading for faster performance.

### What's next for LoFi Steampunk
We have several ideas to expand and improve LoFi Steampunk:
- **Customizable Settings**: Allow users to tweak the audio settings, such as tempo and chord types, to personalize their experience.
- **Additional Visual Themes**: Expand the visual library with more steampunk backgrounds or alternative themes, like cyberpunk or nature-inspired settings.
- **Mobile App Version**: Develop a mobile app version of LoFi Steampunk to provide an even more immersive experience on the go.
- **Extended Sound Library**: Introduce more sounds and effects, allowing users to add layers like drums, ambient sounds, or effects to their music.
- **Save & Share Feature**: Enable users to save their favorite chord progressions or even share their unique creations with others.

Team members:
- [Arnav Kucheriya](https://github.com/ArnavKucheriya)
- [Daniel Matthews](https://github.com/dmw22)
- [Soe Wai Yan Lwin](https://github.com/SoeWaiYanLwin)
- [Subodh Kathayat](https://github.com/subodh10000)
