
# Help Desk Ticket 001: Slow Computer

## 1. Ticket Information

- **Ticket ID:** SAMPLE-001
- **Issue category:** Computer performance
- **Priority:** To be assessed
- **Status:** Open
- **Date reported:** Practice scenario
- **Assigned technician:** Trainee IT Support Technician

## 2. User Report

**Scenario:**

A user reports that their Windows computer has become slow. Applications take longer than usual to open, and switching between applications is difficult.

The cause of the problem has not yet been established.

## 3. Initial Assessment

**Questions to ask the user:**

1. When did the issue begin?
2. Is the entire computer slow or only certain applications?
3. Does the problem occur all the time?
4. Were any changes made recently?
5. Are there any error messages?

**User responses:** Not yet collected.

## 4. Investigation Plan

| Check | Purpose | Result |
|---|---|---|
| Review Task Manager | Identify possible resource bottlenecks | Not tested |
| Check startup applications | Identify unnecessary startup activity | Not tested |
| Check available storage | Determine whether storage is limited | Not tested |
| Review recent changes | Identify possible contributing factors | Not tested |
| Test application performance | Check whether the issue persists | Not tested |

## 5. Investigation Findings

**CPU usage:** 94% at the time of observation.

**Memory usage:** 92% at the time of observation.

**Disk usage:** 35% at the time of observation.

**Top process reported:** Microsoft Edge.

**Microsoft Edge CPU usage:** 37.8% at the time of observation.

**Microsoft Edge memory usage:** 530 MB at the time of observation.

**Computer behaviour:** The computer was reported to be running slowly.

**Interpretation:** Overall CPU and memory utilisation were high at the time of observation. Microsoft Edge was using 37.8% CPU and 530 MB of memory. Its CPU activity may be contributing to the reported slowdown, but further investigation is required to determine whether it is the primary cause. Disk activity at 35% does not, by itself, establish a disk bottleneck.

**Next action:** Monitor CPU and memory utilisation, identify other resource-intensive processes, and investigate Microsoft Edge's activity before applying a corrective action.

## 6. Actions Taken

No troubleshooting actions have been performed yet.

Record each action here after it is carried out, including the observation or result.

## 7. Resolution

- **Root cause:** Not determined.
- **Solution applied:** None yet.
- **Verification:** Pending.
- **User confirmation:** Pending.

## 8. Escalation Notes

Escalate if the issue remains unresolved, hardware failure is suspected, or specialist access is required.

Include investigation findings and tests performed before escalation.

## 9. Final Status

**Current status:** Open — investigation pending.

### 10. Follow-up observations

**Overall CPU usage:** 31% at the latest observation, compared with 54% in the previous observation and 94% initially.

**Overall memory usage:** 87% at the latest observation, compared with 94% in the previous observation and 92% initially.

**Microsoft Edge CPU usage:** 3.8% at the latest observation, compared with 37.8% previously.

**Microsoft Edge memory usage:** 583.9 MB at the latest observation, compared with 530 MB previously.

**Other processes observed by memory usage:**
- Visual Studio Code: 136 MB.
- Task Manager: 55.9 MB.

**Interpretation:** CPU utilisation has decreased across the recorded observations. Memory utilisation has also decreased from its most recent peak but remains high at 87%. Microsoft Edge's CPU utilisation has decreased substantially, while its reported memory usage has increased. These observations do not establish the root cause of the original slowdown.

**Next action:** Check the computer's total installed RAM, memory in use, and available memory in Task Manager before deciding on further corrective action.

### 11. System memory assessment

**Total installed RAM:** 4 GB.

**Memory in use:** 3.4 GB at the time of observation.

**Available memory:** 500 MB at the time of observation.

**Interpretation:** The computer has 4 GB of installed RAM, with approximately 3.4 GB in use and 500 MB available. This indicates limited available memory at the time of observation and may contribute to the reported slowdown. Further investigation is required to determine whether memory pressure is the primary cause.

**Next action:** Monitor memory usage while the computer is idle and during normal use. Check whether performance improves when unnecessary applications or browser tabs are closed, and document the results.

### 12. Controlled troubleshooting test

**Action taken:** Closed unnecessary Microsoft Edge tabs and waited approximately one minute before checking memory usage and computer responsiveness.

**Memory in use before the test:** 3.4 GB.

**Memory in use after the test:** 3.3 GB.

**Available memory before the test:** 500 MB.

**Available memory after the test:** 590 MB.

**Observed outcome:** The computer was reported to be more responsive after the test.

**Interpretation:** Memory in use decreased by approximately 0.1 GB, while available memory increased by 90 MB. The improvement in responsiveness is consistent with the possibility that reducing browser workload helped. However, the test does not establish that Microsoft Edge was the sole cause of the slowdown.

**Current status:** Improvement observed; further verification required.

**Next action:** Continue monitoring system performance during normal use. If the slowdown returns, record CPU and memory utilisation and investigate the processes consuming the most resources before considering further corrective action.

### 13. Final follow-up observation

**Overall CPU usage:** 0% at the time of observation.

**Overall memory usage:** 88% at the time of observation.

**Computer responsiveness:** The computer was responsive during the follow-up check.

**Outcome:** Performance improved following the earlier troubleshooting test. The computer remained responsive during this observation, although memory utilisation was still high.

**Conclusion:** The reported slowdown was not present during the latest check. The available evidence does not establish a definitive root cause or confirm that the issue is permanently resolved.

**Recommended follow-up:** Continue monitoring the computer during normal use. If the slowdown returns, collect new resource utilisation readings and investigate further.

**Ticket status:** Monitoring / pending confirmation of sustained improvement.

*This is an illustrative training ticket. It does not represent an actual customer incident or a completed troubleshooting investigation.*
