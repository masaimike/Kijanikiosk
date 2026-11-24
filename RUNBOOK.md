RECOVERY STEPS FOR FAILED DEPLOYMENTS

1. STOP AND ASSESS
   Halt any further rollout immediately. Check logs, monitoring dashboards,
   and error alerts to identify what failed and how far the impact spreads
   (which services, regions, and users are affected).

2. COMMUNICATE
   Notify the team and stakeholders right away. Open an incident channel,
   assign an incident lead, and post a short status update with the
   impact and the next update time.

3. ROLL BACK TO THE LAST KNOWN GOOD VERSION
   Revert to the previous stable release (redeploy the prior build,
   switch traffic back in a blue/green setup, or disable the feature flag).
   Restore database or config changes if they were part of the release.

4. VERIFY RECOVERY
   Run health checks and smoke tests. Confirm error rates, latency, and
   key user flows are back to normal before declaring the incident over.

5. INVESTIGATE AND PREVENT RECURRENCE
   Hold a blameless post-mortem. Document the root cause, timeline, and
   fixes. Add tests, checks, or deployment safeguards (canary releases,
   automated rollbacks) to prevent it from happening again.
