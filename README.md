# Chainstory

## Overview

The Collaborative Storytelling Platform is an interactive web-based application aimed at redefining storytelling for the digital age. This platform enables users to co-create stories in a turn-based manner, allowing for an ever-evolving, multi-authored narrative experience. Participants can initiate a story and set rules for entry lengths, providing structural guidance while preserving creative freedom.

## Usage

### Step 1: Clone the project

```bash
git clone https://github.com/Npmauney/Chain-story-writing-app.git 
```

### Step 2: Install Dependencies

```bash
yarn # Inside the project directory ie. cd Chain-story-writing-app
```

### Step 3: Run the project

```bash
yarn dev # Starts the development server
```

```bash
yarn build # Builds the app for production.
```

```bash
yarn start # Runs the built app in production mode
```

We suggest that you begin by typing:

```bash
cd Chain-story-writing-app
```

```bash
yarn dev
```

## Features

- Next.js 13 App Directory
- Radix UI Primitives
- Tailwind CSS
- Icons from [Lucide](https://lucide.dev)
- Dark mode with `next-themes`
- Tailwind CSS class sorting, merging and linting.

### Story Initialization

- **Create a New Story**: Users can initiate a new story by providing a title, setting, and opening lines.
- **Entry Length Limit**: The story creator can define how long each entry can be, ranging from one sentence to multiple paragraphs.
- **Guidance Tags**: Optional tags can be added for genre, themes, and plot direction to give collaborators an idea of the intended narrative.

### Collaboration

- **Join a Story**: Users can join existing stories and participate in shaping the narrative.
- **Turn-Based Writing**: Once joined, the platform maintains a queue to manage turns for contributing to the story.
- **Real-Time Notifications**: Users will receive notifications when it's their turn to write, and also when a new entry has been added to a story they are part of.

### Story Progression

- **Live Updates**: Stories are updated in real-time as new entries are added.
- **Historical View**: All past entries can be viewed, and the story's development can be traced back to its origins.
  
### Community and Sharing

- **Upvotes and Comments**: Users can upvote their favorite entries and stories, as well as comment to discuss ideas or suggest plot twists.
- **Social Media Integration**: Easy sharing options to popular social media platforms.
- **Publishing Option**: Completed stories can be published within the platform or exported for offline reading and sharing.

## Technologies Used

- Frontend: ReactJS
- Backend: Node.js with Express
- Database: MongoDB
- Real-Time Communication: Websockets

## Target Audience

- Writers looking for collaborative opportunities
- Readers interested in dynamic, evolving narratives
- Educators in creative writing
- Role-playing communities

## Business Model

- Freemium: Basic access is free with limitations on the number of stories one can initiate or join.
- Premium Subscription: Unlock advanced features like custom entry length, priority queues, and more.

## Milestones

1. **Q1**: Concept Development and Market Research
2. **Q2**: MVP Development
3. **Q3**: Beta Testing
4. **Q4**: Official Launch

By leveraging collective creativity, the Collaborative Storytelling Platform offers a unique, engaging, and interactive way to experience storytelling in the 21st century.

## License

Licensed under the [MIT license](https://github.com/shadcn/ui/blob/main/LICENSE.md).
