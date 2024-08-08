# Ambulatory accelerometer setup and data extraction

## Device details

- Company: [Activinsights](https://activinsights.com)
- Device: [GENEActiv](https://activinsights.com/technology/geneactiv/)

## Software

- [From Activinsights website](https://activinsights.com/support/geneactiv-support/)
- [Local copy of install file](https://mqoutlook.sharepoint.com/:f:/r/sites/o365-group-vascularresearch/Shared%20Documents/General/software/Activinsights%20Geneactiv?csf=1&web=1&e=MOHOTb)

## Instructions

- [Company provided instructions](GENEActiv-Instructions-for-Use.pdf)
- Settings used by Isabella Tan in ambulatory blood pressure study:
  - measurement frequency: set at highest rate
  - period: 24 hours
  - data converter (after export): using epochs of 30 seconds, following convention after informal review of literature.
  - Note: Data export, and data conversion, can take several minutes.

## Data analysis

R markdown scripts are provided by the company. At this stage, no BPAF internal code has been generated for data analysis.

- [Activity report Rmarkdown files](https://github.com/bpaflab/bpaf/tree/main/code/historical%20undocumented%20%20code/Activinsights_Activity_Report_May21_v1)
- [Sleep report Rmarkdown files](https://github.com/bpaflab/bpaf/tree/main/code/historical%20undocumented%20%20code/Activinsights_Sleep_Report_May21_v1)