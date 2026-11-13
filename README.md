# Sales and collections dashboard

A working browser demo for a fictional distributor. Switch month and region to see net sales, cash collected, closing receivables, and gross margin update together.

## Run the demo

Download [index.html](index.html) using GitHub's download button and open it in any modern browser. The demo runs offline with its sample data embedded.

## Questions this dashboard answers

| View | Decision it supports |
| --- | --- |
| Net sales and cash collected | Identify regions where sales activity is outpacing collections and investigate payment timing. |
| Closing receivables | Prioritize regions for a follow-up review. Closing balance includes amounts that may still be within payment terms. |
| Gross margin and gross margin rate | Identify where pricing, mix, or cost warrants a closer look. |
| Regional detail | See which region drives the aggregate movement before assigning an action. |

Closing receivables equal opening receivables plus net sales less cash collected. The fictional dataset treats all sales as credit sales and excludes credits, write-offs, and returns. Gross margin equals net sales less cost of goods sold. The combined margin rate uses total gross margin divided by total net sales.

The figures are synthetic and denominated in BDT.
