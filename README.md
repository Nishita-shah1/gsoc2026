# R Test Solutions
This repository consolidates all my GSOC 2026 test submissions for the animint2 project.
Each solution is implemented in R and includes an interactive visualization hosted on GitHub Pages.

---

## Solutions

### 1. Easy Test Solution
- **Gradient Descent Visualization**: [Animation](https://nishita-shah1.github.io/animint-viz/)
- **Source Code**: [figure-combined.R](https://github.com/Nishita-shah1/animint/blob/main/figure-combined.R)
- **Error demonstration**: When `animint2` is loaded at the same time as standard `ggplot2`, function masking occurs, leading to conflicts.
  ```
  Attaching package: 'animint2'
  The following objects are masked from 'package:ggplot2':
  ```
  Functions like `geom_point`, `geom_line`, `geom_rect`, `geom_segment`, `geom_text` are masked by `animint2` versions.

---

### 2. Medium Test Solutions

**Bisection Method**
- **Demo**: [Animation](https://Nishita-shah1.github.io/bisection-animint/)
- **Source Code**: [bisection_animint.R](https://github.com/Nishita-shah1/bisection-animint/blob/main/bisection_animint.R)

---

**Central Limit Theorem**
- **Demo**: [Animation](https://Nishita-shah1.github.io/clt-animint/)
- **Source Code**: [clt_animint.R](https://github.com/Nishita-shah1/clt-animint/blob/gh-pages/clt_animint.R)

---

**QQ Plot Simulation**
- **Demo**: [Animation](https://Nishita-shah1.github.io/qqnorm-animint/)
- **Source Code**: [qqnorm_animint.R](https://github.com/Nishita-shah1/qqnorm-animint/blob/gh-pages/qqnorm_animint.R)

---

**Moving Window Auto-Regression**
- **Demo**: [Animation](https://Nishita-shah1.github.io/mwar-animint/)
- **Source Code**: [mwar_animint.R](https://github.com/Nishita-shah1/mwar-animint/blob/gh-pages/mwar_animint.R)

---

**Simple Random Sampling**
- **Demo**: [Animation](https://nishita-shah1.github.io/sample-animint/)
- **Source Code**: [simple_random_sampling.R](https://github.com/Nishita-shah1/sample-animint/blob/gh-pages/simple_random_sampling.R)

---

### 3. Medium-Hard Test Solution
- **Gallery**: [Animation](https://nishita-shah1.github.io/nishita-animint-gallery/)
- **Source Code**: [nishita-animint-gallery](https://github.com/Nishita-shah1/nishita-animint-gallery)

---

### 4. Hard Test Solution
- **Video Demonstration**: [YouTube](https://youtu.be/CWurjqqPWLA)
- [hard tests each in very detail](https://www.youtube.com/watch?v=htay3fXV-7s)
- **Pull Request**: [animint/animint2#315](https://github.com/animint/animint2/pull/315)
