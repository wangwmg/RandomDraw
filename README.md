# Random Draw System

English | [简体中文](README_zh-CN.md) | [繁體中文](README_zh-TW.md)

## Overview

The Random Draw System is a simple and efficient web-based application designed to conduct random draws based on inputted data. Whether you're organizing a raffle, team selection, or any event requiring randomized outcomes, this tool offers a secure and intuitive experience. All processing is done locally within your browser, ensuring complete data privacy.

## Features

- **Local Processing:** All random draws are performed locally in your browser, so your data never leaves your device.
- **Customizable Inputs:** Enter formatted data with names and corresponding times to tailor the results to your specific needs.
- **Flexible Draw Options:** Set the number of results to generate and the maximum `times` a name can be included in the draw.
- **User-friendly Interface:** The system features a clean and responsive interface that works seamlessly across modern browsers.
- **Result Tracking:** The system logs the time of the draw and tracks the number of times the draw button has been clicked since the page was opened.

## Usage

1. **Input Data:** Paste formatted data into the text area. The format should be `name times` (e.g., `Xiaoming 3`), where `name` is the participant's name and `times` represents how many times they have participated in activities before this draw.
2. **Configure Draw Settings:**
   - Enter the number of results to generate.
   - Set the maximum `times` value, indicating that if a participant's `times` is less than or equal to this value, they will have a chance of being drawn (regardless of their `times` value, all participants have the same probability of being selected).
3. **Generate Results:** Click the "Generate Random Results" button. The system will perform the draw based on the inputted data and settings.
4. **View Results:** Results will be displayed below the button, showing the selected participants along with their original `times` values, the random seed used for the draw, and the exact time the draw occurred.

## License

This program is licensed under the GNU General Public License v3.0. You may obtain a copy of the license at [https://www.gnu.org/licenses/gpl-3.0.html](https://www.gnu.org/licenses/gpl-3.0.html).

- You can use, modify, and distribute this software under the same license.
- Any modifications must be shared under the same terms.
- No additional restrictions beyond the GPL can be imposed on this software.

## Contributing

Contributions to this project are welcome! If you have ideas for improvements, bug fixes, or new features, feel free to fork the repository and submit a pull request. Any contributions to help enhance the system are appreciated.

## Author

This system was developed by [wangwmg](https://github.com/wangwmg). For any questions or suggestions, please submit an issue on the [GitHub repository](https://github.com/wangwmg/RandomDraw).

---

**Disclaimer:** This program is distributed in the hope that it will be useful, but WITHOUT ANY WARRANTY; without even the implied warranty of MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE. See the GNU General Public License for more details.
