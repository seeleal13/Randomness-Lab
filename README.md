#  Randomness Lab

**Randomness Lab** is an interactive, educational website that showcases
different types of Random Number Generators (RNGs).
It lets you explore, visualize, and compare how algorithms like **Linear
Congruential Generator (LCG)**, **Xorshift**, **Middle Square**,
**Multiplicative Congruential**, and browser **Crypto RNG** behave ---
with real-time graphs, statistics, and entropy demonstrations.

------------------------------------------------------------------------

##  Features

-   **Interactive Generators**
    -   Pseudo-Random (LCG) with seed control\
    -   Cryptographically Secure RNG (`window.crypto`)
    -   Physical RNG (mouse movement / touch gestures)
    -   Advanced RNGs: Xorshift, Middle Square, Multiplicative
        Congruential
-   **Visualizations**
    -   Real-time line charts using HTML5 Canvas\
    -   Statistics: current value, count, average, entropy/cycle
        detection
-   **Educational Comparisons**
    -   Pros, cons, use cases, and historical notes for each RNG\
    -   Side-by-side comparisons of algorithms
-   **Accessible Implementation**
    -   Built with **vanilla HTML, CSS, and JavaScript**
    -   No external dependencies --- runs directly in the browser

------------------------------------------------------------------------

##  Project Structure

    index.html   # Main single-page website
    assets/      # (optional) Place for images, icons, etc.

Everything is contained in **`index.html`**. Just open it in any modern
browser to explore.

------------------------------------------------------------------------

##  Getting Started

1.  Clone the repository:

    ``` bash
    git clone https://github.com/your-username/randomness-lab.git
    cd randomness-lab
    ```

2.  Open `index.html` in your browser.
    That's it! No build steps or installations required.

------------------------------------------------------------------------

##  Motivation

The idea came from a real experience:
I once faced a **fraud ban** after using a basic `random.randint` to
generate keystroke delays.
That made me realize standard randomness isn't truly random --- and can
be detected.

This project is meant to **educate** others about how computers generate
random numbers, their limitations, and why understanding randomness is
important.

------------------------------------------------------------------------

##  Bugs & Contributions

If you find a bug or have a suggestion, feel free to **open an issue**
or **submit a pull request**.
Alternatively, you can **ping me on Slack** (`@seeleal`) for
direct bug reports.

------------------------------------------------------------------------
by Seeleal13
