# Resident Satisfaction Analytics

A four-notebook pipeline that turns maintenance tickets and survey feedback into actionable customer-experience metrics.

## Pipeline

1. **Nb_Maintenance_Tickets_Preprocessing** — cleans ticket and event-log data and engineers features: ticket volumes, fixing/closure status, contractor and part wait times, schedule dates, and ticket-type features, joined with site-to-region mapping.
2. **Nb_Efficiency_Analysis** — measures maintenance efficiency per property: reopen rates, resolution times, ticket age, and ticket repetition.
3. **Nb_Satisfaction_Analysis** — aggregates survey feedback scores by site and date, weights response types, and tracks satisfaction trends to surface properties with significant declines.
4. **Nb_Sentiment_Score** — extracts written survey responses, filters for new comments, and scores sentiment for the satisfaction pipeline.

## Stack

PySpark, Microsoft Fabric lakehouse.

## Notes

Internal identifiers are anonymized and notebook outputs are cleared because the originals ran on internal data.
