# React + TS Custom Boilerplate

This is a **React** application built using **Vite** with **TypeScript**.

## Getting Started

Follow the steps below to set up and run the project locally.

### Clone the Repository

```sh
git clone https://github.com/Stabarak/boilerplate-react-ts.git
cd boilerplate-react-ts
```

### Install Dependencies

```sh
npm install
```

### Start the Development Server

```sh
npm run dev
```

### Build for Production

```sh
npm run build
```

The production-ready files will be in the **dist/** folder.

## Tech Stack

- React
- Vite
- Typescript

## Fetch Boilerplate into an Existing Repo

If you've already cloned your new project repo and need to bring in the boilerplate code, run this commands:

```sh
#!/bin/bash
BOILERPLATE_REPO="https://github.com/Stabarak/boilerplate-react-ts.git"

# Step 1: Add the boilerplate repo as a temporary remote
git remote add boilerplate "$BOILERPLATE_REPO"
echo "Added boilerplate repo: $BOILERPLATE_REPO"

# Step 2: Fetch the boilerplate code
git fetch boilerplate
echo "Fetched boilerplate code"

# Step 3: Checkout the boilerplate code without affecting Git history
git checkout boilerplate/main -- .
echo "Applied boilerplate code to the current project"

# Step 4: Commit and push changes
git add .
git commit -m "Init commit with react+ts template"
git push origin main
echo "Boilerplate successfully merged into the project and pushed!"

# Step 5: Remove the temporary boilerplate remote
git remote remove boilerplate
echo "Removed temporary boilerplate remote"
```
