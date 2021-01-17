# PoseCheck-
Project made for Hack The North 2020++

DEMO VIDEO LINK : https://www.youtube.com/watch?v=LL488qE0xGg&feature=emb_logo&ab_channel=KartikeyS

Inspiration
With everyone stuck at home due to the COVID pandemic, at-home-workouts have been more popular than ever. However, for many of us jumping into the world of fitness for the first time, exercising with proper form is challenging. Yet, without any coach or workout buddies, it's hard to identify where we need to improve. SuperPose is a software solution that highlights areas of improvement in your technique to optimize your movements.

What it does
Users upload a gold standard reference image alongside a photo of themselves, both performing the same desired action. SuperPose compares the two images and shows the similarity between the user's form to that of the reference.

How we built it
We created a website using React. React is a very dynamic web framework that allowed us to handle a multitude of user flows without having to reload the page. TensorFlow.js was used to process the images and compare the two resulting pose vectors.

Challenges we ran into
Inter-team communication was difficult due to the virtual nature of the hackathon. Additionally, our team did not have enough experience regarding some APIs we were hoping to use, so numerous ideas regarding this app had to be scrapped.

Accomplishments that we're proud of
We utilized the TensorFlow.js package to generate the pose position vectors for single-agent images. We analyzed the position data and summarized key results after data comparison. We also successfully integrated this with a dynamic website to provide an interactive user experience.

What we learned
Managing and integrating different development frameworks, especially with unfamiliar programming languages, is very challenging. Our team was grateful for the eye-opening learning opportunity and look forward to tackling our future projects with more developer experience under our belts.

What's next for SuperPose
We aim to integrate a video analysis mechanism that can provide a frame-by-frame comparison of poses. We also hope to add a wireframe visualization method that superposes the two videos to allow users to see the exact differences between their movement and that of the reference.


