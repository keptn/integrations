name: "🔌 New Tool Integration"
description: Keptn should integrate with this tool. Let's make it happen...
title: "[integration] "
labels: "integrations"
body:
  - type: markdown
    attributes:
      value: |
        Keptn is designed to work with any tool. Use this form to request a new integration for a tool you use.

        Before you start!
        
        Keptn comes with two very powerful services recommended as part of a standard install. 80 - 90% of usecases can be handled by one of these two services.
        
        1. The [job executor service](https://github.com/keptn-contrib/job-executor-service) can run any container or script (PowerShell, Shell or Python)
        1. The [webhook service](https://github.com/keptn/keptn/tree/master/webhook-service) (comes preinstalled with Keptn) which can be used with any third party tool that accepts an incoming webhook HTTPS call (eg. `GET`, `POST` or `PUT`).

        That said, it is still valuable to document tool integrations on Keptn which use one of these two services.
        
        So in short, if you use a tool and it ISN'T listed [on the Keptn integrations page](https://keptn.sh/docs/integrations), fill out this form and let us know!
        
        
  - type: input
    id: tool
    attributes:
      label: "Tool / Product Name"
      description: "What tool / product / project would you like to use with Keptn?"
    validations:
      required: true

  - type: textarea
    id: tool_how
    attributes:
      label: "Goal"
      description: "What are you looking to achieve with this integration?"
      placeholder: "eg. I want to trigger this tool from a Keptn task"
      render: shell

  - type: checkboxes
    id: joined_slack
    attributes:
      label: "#help-integrations on Slack"
      description: "I have joined #help-integrations channel on [Keptn Slack](https://slack.keptn.sh)."
      options:
        - label: "Yes"
          required: true

  - type: checkboxes
    id: existing_integrations
    attributes:
      label: No Existing Integrations
      description: I have checked [here](https://keptn.sh/docs/integrations) that an integration does not already exist.
      options:
        - label: "Yes"
          required: true

  - type: dropdown
    id: assisted
    attributes:
      label: Assisted
      description: |
        Are you willing to assist during development of this integration?
        Integration requests that are "assisted" (that is, the requester [you] are willing to assist in developing this integration) will have a higher priority.
      options:
        - "Yes"
        - "No"
    validations:
      required: true

  - type: textarea
    id: other_info
    attributes:
      label: Any other info?
      description: Any other info that might assist in developing / prioritising this integration?
