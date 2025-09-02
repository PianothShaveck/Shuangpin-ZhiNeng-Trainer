# Shuangpin ZhiNeng Trainer

An interactive web trainer to help you master the ZhiNeng ABC (智能ABC) Shuangpin layout for Pinyin input. This tool is designed to teach the initial (声母) and final (韵母) key mappings progressively, one key at a time, using a Spaced Repetition System (SRS) for efficient and long-lasting memorization.

It was made almost entirely by GPT-5.

[**➡️ Live Demo**](https://pianothshaveck.github.io/Shuangpin-ZhiNeng-Trainer/)

## Features

-   **Progressive Learning**: Start with just two keys and gradually add more as you gain confidence. The app suggests the next best key to learn based on a recommended order.
-   **Spaced Repetition System (SRS)**: Incorrectly typed combinations will appear more frequently, while mastered ones are shown less often, optimizing your practice time.
-   **Real-time Performance Stats**: Track your progress with live stats for speed (CPM - Characters Per Minute), accuracy, and total time.
-   **Interactive Keyboard**: A visual keyboard display highlights active keys, expected input, and provides Shuangpin labels for reference.
-   **Customizable Training**:
    -   Manually pick which keys you want to practice.
    -   Filter exercises to show **only valid/common Mandarin syllables**, avoiding mechanical and non-existent combinations.
-   **User Interface Options**: Toggle the visibility of Shuangpin key labels and code hints to increase the difficulty as you improve.
-   **No Installation Required**: Runs entirely in your browser. Your progress, active keys, and stats are saved automatically in your browser's local storage.
-   **Lightweight & Fast**: Built with vanilla HTML, CSS, and JavaScript with no external dependencies.
-   **Multi-language UI**: Supports English, Italian, and Chinese.

## How It Works

Shuangpin ("dual spell") is a Pinyin input method that maps every possible Pinyin initial and final to a specific key on a QWERTY keyboard. This allows you to type any Mandarin syllable with exactly two keystrokes.

This trainer helps you build the necessary muscle memory by breaking down the learning process:

1.  **Start Small**: You begin with a small set of active keys (default: `f` and `j`).
2.  **Practice Combinations**: The app generates all possible initial/final combinations from your active keys (e.g., `f` as an initial + `j` as a final = `fan`).
3.  **Learn & Repeat**: You type the two-key code for the displayed Pinyin. The SRS learns which combinations you find difficult and prioritizes them.
4.  **Expand Your Set**: Once you're comfortable, you click `+ Add key` to introduce a new key and all its associated initials/finals into your practice pool.

This method ensures you are never overwhelmed and can build a solid foundation before moving on to more complex combinations.

## How to Use

1.  **Open the [Live Demo](https://pianothshaveck.github.io/Shuangpin-ZhiNeng-Trainer/).**
2.  The trainer will start with the default keys. Look at the Pinyin syllable presented on the screen.
3.  Type the two corresponding keys on your keyboard (one for the initial, one for the final).
4.  The interface will give you immediate feedback.
5.  When you're ready to learn more, click the **`+ Add key`** button to add the next recommended key to your training set.
6.  Use the controls to customize your session, such as filtering for valid syllables or resetting your progress.

## Technologies Used

This is a dependency-free, front-end only project built with:

-   **HTML5**
-   **CSS3** (with custom properties for easy theming)
-   **Vanilla JavaScript (ES6+)**

## Contributing

Contributions, issues, and feature requests are welcome! Feel free to check the [issues page](https://github.com/pianothshaveck/Shuangpin-ZhiNeng-Trainer/issues) if you want to contribute.

## License

This project is licensed under the MIT License.