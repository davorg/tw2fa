# tw2fa

Convert TransferWise CSVs into a format that FreeAgent recognises

I don't know why FreeAgent and TransferWise don't talk to each other, but this simple Perl program seems to fix the problem.

## Usage

    $ tw2fa ~/Downloads/statement_GBP_2020-03-01_2020-07-01.csv > FreeAgent.csv
