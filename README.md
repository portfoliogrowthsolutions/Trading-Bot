<div align="center">
<br>
<p align="center">
<img src="assets/jesse-logo.png" alt="Jesse" height="72" />
</p>

<p align="center">
Algo-trading was 😵‍💫, we made it 🤩
</p>
</div>

---

BluestarAI is an advanced crypto trading framework that aims to **simplify** **researching** and defining **YOUR OWN trading strategies**.


## Screenshots

Here are a few screenshots just to get you excited:

**Backtest results:**

![image](assets/screenshots/quantstats.png)

**Example strategy code:**

![image](assets/screenshots/strategy.jpg)

**Live trading (requires [live plugin](https://docs.jesse.trade/docs/livetrade.html)):**

![image](assets/screenshots/live-mode.jpg)



## How to contribute

Thank you for your interest in contributing to the project. The best way to contribute is by **participating in the community** and **helping other users**. 

You can also contribute by submitting **bug reports** and **feature requests** or writing code (submitting PRs) which can be incorporated into Jesse itself.

In that case, here's what you need to know:

- Before starting to work on a PR, please **reach out** to make sure it **aligns** with the **project's roadmap** and **vision**.
- If your PR makes changes to the source code, please make sure to **add unit tests**. If you're not sure how to do that, just check out some of the already existing [tests](https://github.com/jesse-ai/jesse/tree/master/tests).

First, you need to install Jesse from the repository instead of PyPi:

```sh
# first, make sure that the PyPi version is not installed
pip uninstall jesse

# now install Jesse from the repository
git clone https://github.com/jesse-ai/jesse.git
cd jesse
pip install -e .
```

Now every change you make to the code will be affected immediately.

After every change, **make sure** your changes did not **break** any functionality by **running tests**:
```
pytest
```

## Disclaimer
This software is for educational purposes only. USE THE SOFTWARE AT **YOUR OWN RISK**. THE AUTHORS AND ALL AFFILIATES ASSUME **NO RESPONSIBILITY FOR YOUR TRADING RESULTS**. **Do not risk money that you are afraid to lose**. There might be **bugs** in the code - this software DOES NOT come with **ANY warranty**.
