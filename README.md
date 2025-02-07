# CapacitorJS Project Template

This repository is a pre-made template for creating a **CapacitorJS** projects, created by **KanesterP**. It provides an easy setup to help you kickstart your CapacitorJS projects efficiently.

---

## Features of this Template

- **Powered by EsBuild**
  - Esbuild is a super-fast build process for Javascript, Typescript and other web assets.

- **Automatic Minification**
  - This templates provides a automatic minification for your HTML, Javascript, and CSS files during the build process to optimize performance

- **Static Assets Support**
  - This templates could easily manage assets like images, fonts, favicons and other more.

- **Developer Friendly**
  - This template is clean, lightweight setup that works seemlessly with CapacitorJS
  - Ideal for botj beginners and advance developers

---

## Getting Started!

Please follow the steps below to ensure right installation.

### Prerequisities

 - [NodeJS](https://nodejs.org/)
 - [Java & JDK](https://www.java.com)
 - [Android SDK](https://developer.android.com/)(For Android App Development)
 - [Gradle](https://gradle.org/)(For Android App Development)
 - [IOS SDK](https://developer.apple.com/)(For IOS App Development)
 - [XCode](https://developer.apple.com/)(For IOS app development)

 > [!NOTE]
 > This template focuses for on android development than IOS development. Please go to the official site of [CapacitorJS](https://capacitorjs.com) for more details :)

### Installation

1. **Clone the repository**
  - Using git:
    ```bash
    git clone https://github.com/Kanester/CapacitorJs_Project_Template.git
    ```

  - Using git CLI:
    ```bash
    gh repo clone Kanester/CapacitorJs_Project_Template
    ```

2. **Install Dependencies**
    ```bash
    npm ci
    ```

3. **Setup CapacitorJS**
  - Setup CapacitorJs for Android
    ```bash
    ./temp build android
    ```
  - Setup CapacitorJs for IOS
    ```bash
    ./temp build ios
    ```

4. **Run CapacitorJS**
  - Build an android apk
    ```bash
    ./temp run android
    ```
  - Serve a webpage preview
    ```bash
    ./temp run web
    ```

> By executing these command you'll see a android or ios folder and a dist folder.
> dist folder is where minified version of your code is placed.
> android or ios folder is a directory containing your app's source code. This is provided by CapacitorJS, so i recommend to read their [documentation](https://capacitorjs.com/).

### Using the template

Using this template is super easy, just edit the what's inside the src directory.
> [!NOTE]
> DO NOT rename the index.html and index.js inside the src folder or it'll fail.
> You could rename it if you're already familiar with the structure of this template :)

Remember to use this command everytime you modify your code. i dont make the rules, it just what it is :)
```bash
./temp build android
./temp run android
```
or
```bash
./temp build ios
```

> [!NOTE]
> Remember that ./temp is just an executable file i made, to get the full potential of capacitorJS, please read the [documentation](https://capacitorjs.com/).

---

## License

This project is licensed under MIT License. See the [LICENSE](./LICENSE) file for more details.

---

## Author

**KanesterP**
Follow for more random projects! :)
 * Github: [KanesterP](https://github.com/Kanester/)

---

## Contributing

Contributing are welcome! Feel free to submit a pull request or open an issue to help improve this template! :)
