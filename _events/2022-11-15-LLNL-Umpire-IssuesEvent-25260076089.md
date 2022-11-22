---
event_type: IssuesEvent
avatar: "https://avatars.githubusercontent.com/u/60452402?"
user: PaulMullowney
date: 2022-11-15
repo_name: LLNL/Umpire
html_url: https://github.com/LLNL/Umpire/issues/794
repo_url: https://github.com/LLNL/Umpire
---

<a href='https://github.com/PaulMullowney' target='_blank'>PaulMullowney</a> open issue <a href='https://github.com/LLNL/Umpire/issues/794' target='_blank'>LLNL/Umpire#794</a>.

<p>Hypre, Umpire and hipMemGetInfo</p><small>I'm not sure if this is the right place to ask this question. I'm using Hypre with Umpire enabled for AMD GPUs (rocm 5.1.0). In my application, I query the amount of free memory available with hipMemGetInfo after key steps (matrix creation, vector creation, preconditioner setup, ...). The results of these calls when not using Umpire are: