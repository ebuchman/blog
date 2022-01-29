---
title: "Velocity of Money"
date: 2022-01-09
draft: false 
---


One of the great mysteries of money is its so called velocity:

{{< tweet 1453092759418523649 >}}

Velocity is defined most traditionally through the Equation of Exchange,
as the ratio of total spending to total amount of money: `V = PQ / M`, where V
is velocity, M is total money supply, and PQ is total spending (the product of
P, a vectors of prices, and Q, a vector of quantities of goods). 
Velocity is like a frequency - it's the number of times a unit of money is used to make a transaction. 
If there's more spending than the total money supply, the same unit of money is being used multiple times.

Both total money and spending are relatively straightforward to measure, 
and thus its easy to compute velocity from them. But its more difficult to measure velocity directly.
One could imagine trying to measure velocity by giving each coin or
bank note a serial number, and recording it as part of each transaction, so you
could see how many times a given coin was literally used (and then average over
them). But it's not clear how this would apply to ledger-based or electronic systems where there are 
no distinct monetary tokens like coins, just balances in an account. So
velocity, at least in the sense that a given unit of money moves,
may not really be a measure itself, but rather something that falls out of
the identity that relates money to spending.

Another way to think about velocity is via it's inverse. If velocity is a
frequency, then its inverse is a duration. If velocity is the number of times a
unit of money is used in transactions, its inverse is the duration of time a unit of money is
held, before it's used in a transaction. This is basically liquidity demand, `D = 1/V`.
If `V = PQ / M`, then rearranging, `M = PQ / V = PQ * D`, which tells us that people do two things with money: spending and holding.

The Equation of Exchange is itself a tautology. What is interesting is
whether it can tell us anything useful about reality. 
This domain has been largely dominated by the Quantity Theory of Money,
the theory that "total spending" in the Equation of Exchange can be decomposed
as the product of scalar aggregates - a price level and an output level - thus
yielding a model of inflationary process in the world: 
given a fixed velocity and output level, more money means higher prices.

The Quantity Theory has its origins in the [Price Revolution] of the 16th
century, as people like Copernicus began to notice the impact that huge
imports of precious metals from the Americas were having on prices. It began to mature
in the writings of John Locke, during the tumultuous years of English monetary
revolution at the end of the 17th century (the founding of the [Bank of England],
the [Great Recoinage]), where Locke played a pivotal role in the institutional
commodification of money. David Hume would elaborate further, in perhaps the
first formalized economic models, on the eve of capitalism's eruption in the mid 18th century. 
John Stuart Mill, one of the leading classical economists, would formalize the Equation of Exchange in the 19th century, and
Irving Fisher would further flesh out the mathematics of the Quantity Theory at the start of the 20th. 
Finally, after WWII, Milton Friedman would erect the entire Monetarist school on the back of the Quantity Theory, bringing it 
to mainstream popularity, and leading to the modern formulation of Central Banks targetting a price-level by manipulating the money
supply.

The Quantity Theory suggests that there are 4 key components of the economy
we can look at or target: the money supply, the price level ("inflation"), the output ("GDP"), and the 
velocity (inverse of "demand for money"). But it has focused us primarily on the money-supply and the price-level, 
assuming that velocity (and thus the demand for money) is largely constant, and that output (GDP) is, well, the output. 
Thus Monetary practice today is largely fixated on targetting a certain price level (eg. 2% inflation), usually by
Central Bank manipulation of the money supply (and the interest rate). 
But Central Banks are finding themselves increasingly unable to meet their inflation targets
(they have chronically and consistently underperformed the 2% inflation standard they set for
themselves, putting aside the recent COVID-induced surge in the CPI), 
as they are increasingly disconnected from the
actual patterns of spending in the economy[^ngdp]. 

The Quantity Theory has always been an extremely limitted and simplified model
of reality. For one, it assumes an underlying temporal process that translates money supply increases into higher prices.
But the Equation of Exchange says nothing about this process' dynamics. For instance, the introduction of new money into an
economy occurs in particular locations (today, primarily in banks), and, and least in principle, flows out into the rest of the
economy over time. It disproportionately benefits those closer to the source - 
this is the [Cantillon effect], well known since at least the 18th century. And in recent times, the "money"[^money] the central banks 
are creating doesn't seem to be making it out into the economy at all. 

The Quantity Theory also assumes that spending, PQ, can be neatly separated into nominal ("price level", P) and real ("output level", Q) components, as
if we can pierce the "neutral veil of money" layered over underlying "real" processes.
But money, especially in the complex credit-economy we live in today, is
by no means a neutral veil - it is a dominant force in the productive organization of society.
Money is a factor of production itself. 

And then there's the matter of velocity,
which adherents of the Quantity Theory generally take to be a constant. But we
know that in times of crisis, velocity collapses (the demand for money
sky-rockets). And given attempts to crank up the money supply in recent decades, measures of velocity appear to be falling everywhere.
The Quantity Theory of Money, then, seems to be of quite limitted value. But what of velocity? Does it
even matter? Does it tell us something meaningful that spending does not?


{{< tweet 1453085016376979456 >}}

Velocity, as we've discussed so far, captures a simple linear relationship
between the money supply and aggregate spending. But Wicksell showed, 
over a hundred years ago, that any amount of money,
even an infintessimally small amount, is in principle sufficient to clear all
the transactions in an economy, assuming the velocity can be made arbitrarily high.
For instance, in a closed economy, where I owe you $5 and you owe me $5, then even with 
only $1 of circulating money supply, we can completely pay off our dues by
sending the $1 back and forth as many times as necessary (ie. 10).
Wicksell extends the example to a larger
society, where payment obligations build up over a period, after which everyone
assembles at a fair to send whatever amount of money exists back and forth until
everyone's debts are cleared. Velocity, then, is somehow a measure of the connectedness of the payments graph,
of the ability for money to flow through it - for a single unit of money to
be used to clear many transactions. 

Wicksell takes the example further by introducing a bank that everyone uses, and
which issues credit (ie. "deposits") that can be used in place of money. 
In such a scenario, where there is effectively no money used for payments, as everyone uses bank credit instead, 
the velocity of money is found to be infinite (ie. spending divided by 0)! Of course today, we consider bank 
credit itself to be money, thus reinstating a non-zero denominator. But the example
highlights that velocity is not just a derived ratio, but a reflection of the
structural reality of the payments network. And that over time, techniques
we've developed to increase the velocity of one kind of money, come to create a
new kind of money themselves. Banknotes are initially a trick to increase the
velocity of metal coins. But over time, banknotes come to be considered money
themselves. And so what was once an increase in velocity, becomes over time an increase in the
money supply. Thus the velocity of money reflects the evolution of the structure of
money itself.

Historically, when money was largely gold and silver coins, velocity was
structurally constrained by the limitted availability of small coins (see [The
Big Problem of Small Change]). The smallest coins were commonly larger than a day or even a weeks worth of
transactions. Thus, certain kinds of spending that people would have liked to
engage in were structurally restricted, since the denominations of currency
simply did not exist to facilitate them. They would have to resort
to barter, or to local credit relationships (running up tabs), which might
provide some relief, but were still severely limitted.
Banking as an institution would come to resolve this particular constraint on
velocity by moving us away from coins towards accounts, and through a couple
centuries of inflation that have made the price of daily transactions much
larger than the smallest units of money. But even still, certain transactions
are infeasible, like so-called "microtransactions". This is a structural
constraint on velocity due to the virtual impossibility of sending high volumes of
small transactions in the current configuration of the payments system. And
this constraint on velocity appears to pose a serious impediment to a more
responsible commercialization strategy for the internet. So velocity, at least
its structural determinants, seems to matter.

What other structural constraints might there be on velocity in the modern
payments system? One obvious one is the interbank clearing system. One way to
understand the structure of the interbank clearing system is that it's been
designed to maximize velocity between banks, making use of as little monetary
reserves as possible to support as large a set of transactions as possible. The
banks have access to extremely high velocity structures within their payments
network, clearing systems that save them trillions in liquidity. But what about the rest of us?

Well the rest of us are limitted by the banks - our balances in their accounts,
and by extension, the credit they're willing to extend us. And so for many
people and businesses, their ability to spend is constrained by their ability to
get payed in bank money. In the natural course of doing business, each
firm builds up a mix of accounts receivables and accounts payable with the
various other entities it engages with. And for calculating its own solvency, it can offset accounts payable
with accounts receivable. But it cannot actually clear its account payable using
accounts receivables, because the receivables aren't money - they're not broadly
accepted media of exchange, but just the IOU of some entity that owes you money.
In order to clear its accounts payable, it needs actual money, which
might only be possible if it can collect on its account receivables. Minsky
called this the survival constraint. As Mehrling says, "you can be insolvent for
a while, but liquidity kills you quick". 

The liquidity constraint is a structural constraint on velocity. It derives from
the gap between genuine money, and any old entity's IOU, which is effectively
the structure of the payment system. Banks seek to relieve the liquidity
constraint for themselves by getting together in groups and netting out all
their accounts receivable and payable between each other. What if businesses
could do the same thing?

In the earlier examples from Wicksell, we sent whatever money we had back and
forth to clear all the payments. And in the example of banks, they establish a
clearing house so each bank only pays or receives from the clearing house,
reducing the number of counterparties. But there's another approach, which does
not require sending money around, and does not require changing the graph of
counterparties (who owes who), but rather looks at the structure of obligation
graph itself, and clears any cycles that exist. If I owe you $5 and you owe Abed
$5 and Abed owes me $5, we can clear all 3 transactions without using any money
at all. This is the magic of credit clearing.

....

demmurage
schumpeter quip
growth in spending should come from structure not inputs
energy flow





