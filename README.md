What It Does?
NevAlone transforms seniors' loved ones into AI companions, accessible via web browsers, SMS, and voice calls. It allows for the upload of cherished memories to AI clones for dementia patients, preserving these memories and reducing the caregiver's burden. The technology provides a continuous connection, even for those who may forget that a loved one has passed away.

How We Built It?
The platform encompasses:
Frontend: Developed using Angular for caregivers and Next.js for seniors, along with a landing page using HTML, CSS, and JavaScript.
Backend: Developed using Node.js, with API endpoints set up using Next.js.
Authentication: Handled using Clerk and Firebase.
Database: Employed Pinecone for vector database functionalities, and firebase for user data.
AI Orchestration: Managed using Langchain.js.
Text Model: Powered by OpenAI.
Text Streaming: Utilized AI SDK.
Conversation History: Stored in Upstash.
Deployment: Handled using Ngrok.
Communication with Companion: Managed via Twilio.
Voice Clone: Implemented using ElevenLabs.

Challenges We Ran Into
The primary challenge was integrating two distinct front ends: a user-friendly Next.js front end for seniors and an administrative Angular front end for caregivers. Achieving seamless connectivity and cohesive operation between these varied technologies was a significant hurdle, but through collaboration and problem-solving, we ensured a harmonious user experience.

Accomplishments
We are proud to have tackled unfamiliar frameworks and built a project with real-world applications, significantly aiding seniors and caregivers. The learning and innovation demonstrated through this project have been immensely rewarding.

What We Learned?
The project provided us with valuable insights into constructing vector databases and the intricacies of connecting front-end and back-end components through APIs.

What's Next for NevAlone?
Looking ahead, we aim to enhance the AI clone phone call feature, recognizing the preference of older users for phone calls. Our goal is to make this experience as realistic, fast, and user-friendly as possible, continuing our mission to support the senior community.

We hope that our project, NevAlone, makes a significant impact and contributes positively to the lives of seniors and caregivers. Thank you for considering our project and we are open to any feedback or contributions to make NevAlone even better!

This code is for the Caregiver side: Here you can view the Senior/Patient Side: https://github.com/tesims/Hack-Harvard
