---
layout: page
title: Learning Reduced Dynamics from Full Equations
description: Using SINDy as a model reduction technique
img: assets/img/575Pic.png
importance: 2
category: class
giscus_comments: true
---

We investigate the feasibility of Sparse Identification of Nonlinear Dynamics (SINDy) as a model reduction technique for the full Euler water wave problem. We apply SINDy to data simulated from the full Euler water wave problem in the regime in which it is well-approximated by the Korteweg--de Vries (KdV) equation for long waves in shallow water. We find that SINDy cannot recover the KdV equation in this case, even after performing cross-validation; however, we determine that SINDy can recover the KdV equation given data simulated directly from the KdV equation itself. Furthermore, we find that given cnoidal solutions to the full water wave problem in the KdV regime, SINDy can recover the KdV equation after cross-validation, but not consistently. We conclude that in its current state, SINDy cannot reliably be used as a model reduction technique.

You can find a detailed report, results, and code <a href='https://github.com/sichinaga/amath575_project'>here</a>.