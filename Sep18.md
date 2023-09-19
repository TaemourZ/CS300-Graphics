# **CLASS NOTES** by Taemour Zaidi

## Line Drawing

- Line equation
    - $y = mx + b$
    - $m$ is slope and $b$ is intercept
    - $m = \frac{y_2 - y_1}{x_2 - x_1}$
    - $b = y_1 - mx_1$
- Line drawing algorithms
    - DDA (Digital Differential Analyzer)
    - Bresenham's

### DDA (Digital Differential Analyzer)
- **If drawing starts from left to right:**
    - if $|m| \leq 1$, then $\Delta x = 1$, $\Delta y = m$
    - if $|m| > 1$ for positive $m$, then $\Delta x = \frac{1}{m}$, $\Delta y = 1$
    - if $|m| > 1$ for negative $m$, then $\Delta x = \frac{-1}{m}$, $\Delta y = -1$
- **If drawing starts from right to left:**
    - if $|m| \leq 1$, then $\Delta x = -1$, $\Delta y = -m$
    - if $|m| > 1$ for positive $m$, then $\Delta x = \frac{-1}{m}$, $\Delta y = -1$
    - if $|m| > 1$ for negative $m$, then $\Delta x = \frac{1}{m}$, $\Delta y = 1$
