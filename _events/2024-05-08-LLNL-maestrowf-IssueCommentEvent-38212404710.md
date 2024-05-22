---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/44277022?"
user: jwhite242
date: 2024-05-08
repo_name: LLNL/maestrowf
html_url: https://github.com/LLNL/maestrowf/issues/441
repo_url: https://github.com/LLNL/maestrowf
---

<a href='https://github.com/jwhite242' target='_blank'>jwhite242</a> commented on issue <a href='https://github.com/LLNL/maestrowf/issues/441' target='_blank'>LLNL/maestrowf#441</a>.

<small>Think this might be what's adding all that extra output on your cluster: https://slurm.schedmd.com/job_submit_plugins.html with some custom validation/logging messages always spit out (I'll wager srun and salloc do the same?).  Haven't found anything yet about whether the order is always to dump out all these log messages prior to the job id line, but seems likely given most of this happens before the actual submission.  Almost think it might be safer to leave the --parseable option off and have that regex account for 'Submitted batch job' prefix on the line so we can be sure the number we detect is actually the one we want?

<a href='https://github.com/LLNL/maestrowf/issues/441' target='_blank'>View Comment</a>