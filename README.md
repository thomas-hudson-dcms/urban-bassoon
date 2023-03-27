Created by Thomas Huson (S&DI) on 27/03/23.

The code in this gist creates an R shiny application, which is used by the BDUK Case Management Team to pre-triage supplier data.

This code contains no senstive information. The code performs checks on (locally) uploaded datasets, such as checking for duplicates and when a technology is full-fibre checking that it's maximum download speed is at least 1000 MBps.

This code is designed to be run locally on RStudio using the runGist() command. The ease in running a secret gist shiny app is why it is being used over a standard GitHub repository. It allows the sensitive data to be kept locally (rather than uploaded to a server) whilst also allowing remote updates to the code (which would be harder for an executable/ locally saved file).

However, there are limitations with using gist. For example the difficulty in collaborating. However, the gist can be forked or cloned into a repository. 