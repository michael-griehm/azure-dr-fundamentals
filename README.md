# Azure DR Fundamentals

This repo contains info and theory related to the fundamentals of Azure Disaster Recovery (DR).

## Defining the terms

Before we can discuss strategies for acheiving a Disaster Recovery stance within a workload running in Azure, we first must define the terms.

### What does 'Disaster' mean?

When I think disaster, two categories come to mind:

- Compute or Storage interruptions due to hardware failure, network failure, power outage, natural disaster, or denial of service attack on a data center.
- Corruption or loss of data due to process error, code bugs, or accidental deletion.

### What does 'Recovery' mean?

When I think or 'Recovery', what I really think of is workloads 'Resilency' to the types of 'Disasters' categorized above.  I define resiliency as the combination of the two questions below:

- What percentage of the workload and/or data can be fully recovered?
- How long does it take for acceptable operations of the workload to be restored?

## The Planes of Azure

You might have heard the terminology, control plane 