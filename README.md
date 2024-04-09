DRAFT DRAFT DRAFT

# SecuredServiceTasks
\
_Secured Service Tasks_ is a security feature add-on to ServiceNow ITSM module to prevent others from viewing records assigned to specific services. This is helpful when your organization processes sensitive information based on various services; e.g. cybersecurity attack surface managment tasks.

This guide is to help ServiceNow admins setup _Secured Service Tasks_ for services. The goal for _Secured Service Tasks_ is to work in conjunction with the default out-of-the-box (OOTB) ServiceNow ITSM module to ensure future upgradeability across ServiceNow releases. 

&nbsp;

---
## Theory & How It Works
\

The basic premise is organizations have teams that support and perform various services. Some services could be considered public and shareable, while other services could be considered private and secured. The secured services should limit who can see the ticket data. 

At the time of this release (Washington) there are 44 OOTB tables that extend the Task [task] table. 
- Asset Reclamation Request [asset_reclamation_request]
- Asset Task [asset_task]
- Business Application Request [business_app_request]
- Catalog Task [sc_task]
- Change Phase [change_phase]
- Change Request [change_request]
- Change Task [change_task]
- Chat Queue Entry [chat_queue_entry]
- CMDB Data Management Task [cmdb_data_management_task]
- CMDB Multisource Recompute Task [cmdb_multisource_recomp_task]
- Deployment Request [sn_deploy_pipeline_deployment_request]
- Developer Collaboration Task [sn_collab_request_dev_collab_task]
- Feature Task [release_task]
- Follow On Task [cert_follow_on_task]
- Group approval [sysapproval_group]
- Guidance Task [help_guidance_task]
- Guided Setup Task [gsw_task]
- Incident [incident]
- Incident Task [incident_task]
- KB Submission [kb_submission]
- Knowledge Feedback Task [kb_feedback_task]
- Orphan CI Remediation [orphan_ci_remediation]
- Private Task [vtb_task]
- Problem [problem]
- Problem Task [problem_task]
- Reclassification Task [reclassification_task]
- Recommended Field Remediation [recommended_field_remediation]
- Remediate Duplicate Task [reconcile_duplicate_task]
- Release Phase [release_phase]
- Renew Lease Task [statemgmt_renew_lease_task]
- Report Access Request [sys_report_access_request]
- Request [sc_request]
- Requested Item [sc_req_item]
- Required Field Remediation [required_field_remediation]
- Roster schedule entry proposal [roster_schedule_span_proposal]
- Scan Task [scan_task]
- Service Task [service_task]
- Stale CI Remediation [stale_ci_remediation]
- Standard Change Proposal [std_change_proposal]
- Ticket [ticket]
- Transfer Order Line Subtask [alm_transfer_order_line_subtask]
- Transfer Order Line Task [alm_transfer_order_line_task]
- Upgrade History Task [upgrade_history_task]
- Zero Touch Refresh Fulfillment Request [sn_itam_ztr_fulfillment_req]
