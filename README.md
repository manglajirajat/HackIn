# HackIn 🚀

**HackIn** is a **developer-centric platform** designed to help programmers track their hackathon journey, showcase their projects, and connect with like-minded developers. Whether you're a seasoned hackathon veteran or just starting out, HackIn provides a unified dashboard to monitor your progress, achievements, and team collaborations.

With HackIn, you can:
- **Track your hackathon participation** and results.
- **Showcase your projects** and skills to the world.
- **Connect with teammates** and build your developer network.
- **Climb the global leaderboard** and earn recognition for your achievements.
- **Organize or join hackathons**
- **Find sponsors** or **sponsor events** to support innovation.

---

## Features ✨

### 1. **Personalized Dashboard**
   - Track your hackathon stats, including participation, wins, and points.
   - Visualize your progress with interactive charts and graphs.
   - Showcase your badges, trophies, and achievements.

### 2. **Project Showcase**
   - Highlight your best projects with detailed descriptions, tech stacks, and hackathon results.
   - Add tags for technologies used (e.g., React, TensorFlow, Solidity).
   - Share your projects with the community and get feedback.

### 3. **Team Collaboration**
   - Create and manage teams for upcoming hackathons.
   - Track team performance and contributions.
   - Connect with teammates and view their profiles.

#### Live vs Private Teams
- When creating a team, choose:
 - **Live**: Your team will appear under “HackMates” and other developers with required skills can request to join.
    - 🔔 **Team leaders receive email notifications** when someone requests to join their team.
    - 📩 **Joiners receive email updates** when their request is accepted or rejected by the team leader.
  - **Private**: A unique **Team Code** will be generated to share directly with friends or collaborators.

### 4. **Global Leaderboard**
   - Compete with developers worldwide and climb the ranks.
   - Earn points for participating in hackathons, winning challenges, and completing projects.
   - Unlock achievements and badges as you progress.

### 5. **Hackathon Tracker**
- Organize hackathons with full control over team applications.
- Stay updated on upcoming hackathons.
- Track your participation history and results.
- Set goals and monitor your progress.

#### Organizer Controls
- Teams can apply to participate in a hackathon.
- Organizers can **accept or reject** team applications to ensure event quality.
  
### 6. **Sponsor Integration**
- Sponsors can register with a **dedicated sponsor account** (only one sponsor profile per account).
- Receive sponsorship requests from hackathon organizers.
- Choose to **accept or decline** sponsorships.
- Accepted sponsored hackathons are displayed on the sponsor’s profile for visibility.

---

## Why HackIn? 🤔

Hackathons are a fantastic way to learn new skills, build projects, and network with other developers. However, keeping track of your progress and showcasing your achievements can be challenging. **HackIn solves this problem** by providing a centralized platform where you can:

- **Organize your hackathon journey** in one place.
- **Showcase your skills** to potential employers or collaborators.
- **Stay motivated** by tracking your growth and competing with others.
- **Connect with sponsors** or **get sponsored** to organize impactful events.
- **Build or discover teams** that match your skills and interests.

---

## How to Use 🛠️

1. **Sign Up**: Create an account on HackIn to get started.
2. **Set Up Your Profile**: Add your details, skills, and interests.
3. **Track Hackathons**: Log your participation and results.
4. **Showcase Projects**: Upload your hackathon projects with descriptions and tech stacks.
5. **Connect with Teams**: Join or create teams (Live or Private mode).
6. **Organize Events**: Host hackathons and manage team approvals and sponsor requests.
7. **Sponsor Events**: Create a sponsor profile and support developer innovation.
8. **Climb the Leaderboard**: Earn points and badges to rise through the ranks.

---
## Environment Variables 🔑

To run this project, you will need to add the following environment variables to your `.env` file:

### Backend Environment Variables
```plaintext
MONGODB_URI =            # MongoDB connection string for database access.
PORT = 3000              # Port on which the server will run.
EMAIL =                  # Email for sending notifications or authentication.
PASSWORD =               # Password for email or authentication.
SESSION_SECRET =         # Secret key for session management.
GITHUB_CLIENT_ID =       # GitHub OAuth app client ID for authentication.
GITHUB_CLIENT_SECRET =   # GitHub OAuth app client secret for authentication.
GITHUB_CALLBACK_URL = http://localhost:3000/api/v1/auth/github/callback  # Callback URL for GitHub OAuth.
CLOUD_NAME =             # Cloudinary cloud name for image uploads.
API_KEY =                # Cloudinary API key for image uploads.
API_SECRET =             # Cloudinary API secret for image uploads.
FIREBASE_PROJECT_ID =    # Firebase project ID for authentication.
FIREBASE_PRIVATE_KEY =   # Firebase private key for authentication.
FIREBASE_CLIENT_EMAIL =  # Firebase client email for authentication.
```

### Frontend Environment Variables
```plaintext
VITE_GITHUB_CLIENT_ID =  # GitHub OAuth app client ID for frontend authentication.
VITE_BACKEND_URL = http://localhost:3000  # Backend API URL for frontend requests.
