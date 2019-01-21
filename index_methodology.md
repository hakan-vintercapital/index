About Vinter Capital
====================

We believe that blockchain technology has the potential to transform our
world. The application of this technology can result in a more
decentralized and transparent economy with far-reaching positive effects
such as financial inclusion for everyone.

The objective of Vinter Capital is to lower the entry barriers that
exist today when investing in cryptocurrencies. We do so by providing
transparent and regulated indices that can be used in financial
products. Our products have the potential of being a bridge between the
professional investment industry and the cryptocurrency community.

BlockchainX indices
===================

The cryptocurrency market is in its infancy. This presents a challenge
to established methods for indexing. BlockchainX indices combine the
best of traditional index methodologies with appropriate adjustments for
cryptocurrency factors such as, liquidity, exchange
stability, custody limitations as well as regulatory requirements.

The BlockchainX index family is developed to provide a rule-based and
transparent way to track the value of cryptocurrencies. All indices are
designed to be regulated investable benchmarks.

All BlockchainX indices are compliant by design. Decisions must be
clear, rule-based, robust, reliable and transparent. The methodology is
developed, operated and administered transparently in compliance with
Article 13 of the Regulation 2016/1011 on indices used as benchmarks in
financial instruments and financial contracts or to measure the
performance of investment funds (the ”BMR”). The key elements of this
methodology are published and made available for each benchmark provided
and published or, when applicable, for each family of benchmarks
provided and published.

This methodology states the regulatory framework for the development,
calculation and administration of the BlockchainX index family.

Input data
==========

Input data requirements
-----------------------

Vinter Capital’s provision of benchmarks shall be governed by the
following requirements in respect to its input data:

-   the input data shall be sufficient to represent accurately and
    reliably the market or economic reality that the benchmark is
    intended to measure;

-   The input data shall be transaction data, if available and
    appropriate. If transaction data is not sufficient or is not
    appropriate to represent accurately and reliably the market or
    economic reality that the benchmark is intended to measure, input
    data which is not transaction data may be used, including estimated
    prices, quotes and committed quotes, or other values;

-   the input data shall be verifiable;

-   clear guidelines regarding the types of input data, the priority of
    use of the different types of input data and the exercise of expert
    judgment shall be published;

-   where a benchmark is based on input data from Contributors, Vinter
    Capital will obtain, where appropriate, the input data from a
    reliable and representative panel or sample of Contributors so as to
    ensure that the resulting index is sufficient to represent
    accurately and reliably the market or economic reality that the
    benchmark is intended to measure.

Vinter Capital will not use input data from a contributor if the
administrator has any indication that the contributor does not adhere to
the code of conduct referred to in Article 15 of the BMR, and in such a
case shall obtain publicly available representative data.

### Contributor selection

The quality of data contributors is assured through the following
controls:

-   Presumable Contributors are evaluated on the basis of data quality,
    cost of sources, reputation and market share.

-   Input data is compared between multiple Contributors in order to
    ensure its integrity and accuracy. In the event of data being
    insufficient or unverifiable, one Contributor will be replaced with
    another.

Continuous evaluation of selected contributors
----------------------------------------------

Reliability of provided data is assessed with respect to availability
and consistency of each data source. Data is compared across multiple
independent data providers. Anomalies, such as abnormal deviation from
average, are investigated. Providers with substantial and persistent
anomalies are at risk of being removed as data contributors to the
BlockchainX indices. Accuracy is verified by comparing contributed data
with other trusted data sources. Furthermore, computation schemes
,such as free-float schemes, are also compared between independent scheme providers.

Data correction procedure
-------------------------

In the case of data corruption, Vinter Capital will immediately inform
stakeholders concerning the error. An investigation into the reasons
behind the corrupted data will take place in order to remove possible
vulnerabilities from data-collection processes. Erroneous computations
are corrected whenever possible. Furthermore, a consequence analysis
will be performed where financial and legal consequences, with respect
to corrupted data, are assessed and a structural review of relevant
computational schemes are performed. Affected clients will then be
informed about the error, its potential legal and financial consequences
and relevant recalculations. Any conduct that may involve manipulation
or attempted manipulation of an index is reported to regulators.

Circulating supply
------------------

Circulating supply for each constituent is determined via:

1.  The summation of all Unspent Transaction Outputs (UTXOs). The
    summation is based on the transaction history of a full node
    controlled by the BlockchainX index committee.

2. The summation of issued cryptocurrency. The summation is performed with respect to previously mined blocks. using the transaction history of a full node controlled by the BlockchainX index committee.

3. If information on issued cryptocurrency is not available, circulating supply is estimated based on the cryptocurrency's specified emission rate and present block number.

4.  Other data sources reviewed by the BlockchainX index
    committee.


Free-float
----------

Free-float equals circulating supply with a potential reduction due to
one or more of the following factors:

-   The amount of cryptocurrency allocated prior to the public release
    of a blockchain and that remain in the control of developers,
    principals, foundations or corporations.

-   Cryptocurrencies that are deemed not accessible to any market
    participant due to loss of private keys, dust-accounts (accounts
    with lower holdings than the current fees or cost associated with
    transfers or creation of a wallet), or burning (a strategy that
    seeks to obtain a price increase by directly reducing the
    circulating supply of a cryptocurrency).

-   Other factors as determined by the BlockchainX index committee.

Issuance will be returned to the free-float circulation in the event of
a public announcement that assets have been sold into the public market.
Free-float adjustments are made on the monthly rebalancing date.

Foreign exchange rates
----------------------

Intra- and interday foreign exchange rates are obtained from WM/Reuters as well as ECB.

Selected exchanges {#sec:selected-exchanges}
------------------

Selected exchanges contribute market data to the computation of the
BlockchainX indices. As of \today, market data is obtained from the following
cryptocurrency exchanges: Bitfinex, OKCoin, Bitstamp, Itbit, Coinbase,
Coinbase Pro, Kraken and Gemini. For an exchange to be selected as a
data contributor it must have:

1.  been operating as a cryptocurrency exchange for a minimum of two
    years.

2.  implemented trading, deposits and withdrawal
    fees without interruption and for the duration of one month.

3.  met a minimum monthly liquidity threshold with respect to total
    trading volume.

4.  for at least one month, provided reliable and valid market data.

5.  for at least one month, offered the possibility to withdraw and
    deposit USD.

6.  chosen a jurisdiction of incorporation that offers sufficient
    investor protection.

7.  complied with relevant regulations such as know your
    customer and anti-money laundering requirements.

8.  provided information concerning ownership and corporate structure.

9.  passed the BlockchainX index committee’s exchange review. The review is an overall assessment of market and operational risks. It includes but is not limited to an evaluation of past
    security breaches, trading cessations, legal disputes and if
    provided market data are to be considered readily available.

Under extraordinary circumstances, exchanges can be added or removed as
data contributor at the discretion of the BlockchainX index committee.

Index methodologies
===================

The BlockchainX index family consists of several indices. The BL10M-U
index contains the 10 largest assets, weighted by market capitalization,
and is denominated in USD. The BL5E-S index contains the 5 largest
assets. It is equally weighted and denominated in SEK. All indices are
listed in the appendix.

Every index is priced using a 20-second average of the BlockchainX
composite constituent price (described in \[sec:BCP\]). Pricing occurs
with 20-second intervals between 00:00 and 24:00 CET.

A daily closing value is calculated at 17:00 CET. The index value is
published in USD, EUR and SEK using validated exchange rates.

Eligible constituents {#sec:eligible-const}
---------------------

Cryptocurrencies trading on *selected exchanges* are eligible as index
constituents in BlockchainX indices if they:

1.  allow for air-gapped cold storage, including offline wallet
    generation and offline transaction signing.

2.  are not pegged to another asset such as currencies or
    commodities.

3.  been traded on two selected exchanges for the duration of one month.

4.  can be deposited and withdrawn from at least two selected exchanges.

5.  are not an ongoing Initial Coin Offering (ICO).

6.  have in the last month had at least 20% of its publicly traded volume located at selected
    exchanges.

7.  have no more than 90% of its monthly trading volume located at a
    single selected exchange.

8.  have a monthly trading volume that exceeds 20% of its circulating
    supply.

9.  have for the past month had a daily trading volume that exceeds USD 20 million.

10. have not been deemed a security, or potential security, by the
    BlockchainX index committee.

11. have not been deemed fraudulent by the BlockchainX index committee.

12. are a cryptographically secured digital bearer instrument.

13. are freely traded and can be freely held for the foreseeable future.

14. maintain an underlying protocol that has been deemed technically and
    cryptographically sound with no known security vulnerabilities,
    including critical bugs, undue exposure to 51% attacks, or other
    factors as determined by the BlockchainX index committee.

Cryptocurrencies that meet these criteria are *eligible constituents*.

Selected constituents
---------------------

*Eligible constituents* (section \[sec:eligible-const\]) are ranked by
market capitalization in descending order. For indices with 10
constituents, the top 8 of the ranked list are selected immediately.
Secondly, constituents that (a) were selected at the previous
rebalancing date and (b) have a rank between 9 and 12 are added to the
selected constituents. Remaining constituents are chosen according to
their market capitalization.

For indices with 5 constituents, the top 3 of the ranked list are
selected immediately. Secondly, constituents that (a) were selected at
the previous rebalancing date and (b) have a rank between 4 and 7 are
added to the selected constituents. Remaining constituents are chosen
according to their market capitalization.

If it is not possible to reach the intended number of constituents, the
BlockchainX index committee can decide to either include non-eligible
constituents or allow the index to have less constituents than intended.

Constituent price (BCP) {#sec:BCP}
-----------------------

All eligible cryptocurrencies are priced using the BlockchainX composite
price algorithm. In order to compute the BlockchainX composite
constituent price (BCP), the algorithm executes three steps.

First, at time $t$, order data on executed trades are obtained from all
selected exchanges with respect to a 20-second time window.

Secondly, for each exchange and constituent, a Volume Weighted Average
Price (VWAP) is computed with respect to executed trades within the
specified time window.

Thirdly, the median of all exchange specific VWAP:s is taken as the BCP
for each constituent.

Missing data is imputed through a nearest neighbor approach with respect
to time. Imputation is performed using data from all selected exchanges.
All BCPs are computed using USD as quote currency. The BCP is then
translated into SEK and EUR using foreign exchange reference rates from
trusted data providers.

Index price and weights
-----------------------

Let the number of selected constituents at time $t$ be denoted as
$k(t)$. Let $w_i(t)$ and $p_i(t)$ be the weight and BCP of asset $i$.
The BlockchainX index price is then given by: $$% \text{BLX}(t) =
  \frac{  \sum_{1}^{k(t)} w_i(t) p_{i}(t)  }{\text{DIV}(t)}
\label{eq:index}$$ where $\text{DIV}(t)$ is a divisor (described in
section \[sec:divisor\]). The weight of asset $i$ at time $t$ is:
$$w_i(t)=
\begin{cases}
    1 / k(t), & \text{for equally weighted indices} \\
    f_{i}(t) /f(t),  & \text{for market capitalization weighted indices}
\end{cases}$$ where $f_{i}(t)$ is the free-float of constituent $i$ and
$f(t)=\sum_1^{k(t)}f_i(t)$, both are recalculated at rebalancing date.

Divisor {#sec:divisor}
-------

Index adjustments, such as monthly rebalancing, should not change the
index value. A divisor is therefore introduced in order to insure that
the index value only fluctuates due to price movements in the underlying
assets and not due to other events that affect total market
capitalization. At inception, the divisor is given by
$$\text{DIV}(0) = \frac{1}{K} \sum_{i}^{k(0)} w_i(0) p_{i}(0)
  \label{eq:initial_divisor}$$ where $K=100$ in order to ensure an
initial index value of 100.

A fee of 2.5 percent per annum is deducted from the divisor on a daily
basis. The closing index price is published daily at 17:00 CET, and the
fee is accounted for by multiplying the previous day’s divisor with
$(1 + 0.025/365)$.

Given a positive number $\delta$, the divisor can be calculated for any
time $t$ recursively via $$\text{DIV}(t)
  = \frac{\sum_{i}^{k(t)}
    w_{i}(t)p_{i}(t)}{\sum_{i}^{k(t-\delta)}
    w_{i}(t-\delta)p_{i}(t-\delta)}
    \text{DIV}(t-\delta)
\label{eq:divisor}$$ which ensures index continuity.

Rebalancing
-----------

BlockchainX indices are rebalanced monthly. All weights $w_i(t)$ have
identical numerical values between rebalances.

The rebalancing window is set to 12:00 CET on the first business day of
the month, plus or minus 24 hours. Rebalancing will occur at a randomly
chosen time during this window. Randomization is used in order to avoid
front-running. Clients subscribed to any of Vinter Capital’s indices
will receive an email containing information about the new weights for
all assets in that index. On the second business day of the month at
16:30 CET, the actual weights are published on Vinter Capital’s website.
The delay is implemented in order to increase the investability of
BlockchainX indices.

Rebalancing involves (i) a review of exchanges, (ii) selecting
constituents and (iii) calculating their weights.

Market events
-------------

Cryptocurrencies have a series of unique market events, compared to
traditional assets, such as forks, staking and airdrops. These events
have the potential to disrupt as well as increase the value and security
of current selected constituents. However, in order to reduce
unpredictable changes in the composition of the index, the BlockchainX
index committee will handle each event with the intention that intra
monthly index return should solely depend on price movements in index
constituents.

### Forks

Formally, a blockchain is a distributed database of a network's transaction history. To own a blockchain's cryptocurrency is to have writing permission to this database. A transaction of
cryptocurrencies is therefore the transferal of these writing
permissions to another user. Blockchains are often developed under an
open source license and can therefore be copied and transformed by any
group of developers. Whenever this happens the developers can choose to keep parts of the transaction history or to erase it. Erasing it means that the developers creates a new cryptocurrency and keeping it means that the blockchain is experiencing what has been named a fork. Forks can occur due to technical disagreements regarding the devel-
opment of the blockchain or to correct certain parts of the transaction history. The old
blockchain’s transaction history is therefore often kept intact or partly intact in order to retain as much of the old network as possible. This
results in that those who held cryptocurrency on the old blockchain find themselves to own an euqal amount of cryptocurrency on the new blockchain.

Forks that occur with respect index constituents can cause uncertainty in the computation of the index since it is not clear which of the two, or more, forks that should be used as the constituent. Forks are also an operational risk for those who seek to track the index since initiating trading of a new cryptocurrency often requires adjustments to trading infrastructure. In order for a fork to be eligible as an index constituent it needs to fulfill all BlockchainX constituent criteria, with exemption of those criteria that are based on historical performance. The eligible fork that is traded on the largest number of *selected exchanges* is then chosen as the constituent. If two or more eligible forks are traded on the same number of exchanges, highest price is used to select a constituent. This selection process continues until next rebalancing date. If prices are unavailable due to trade cessation, or other reasons, a last observation carried forward approach is used to obtain a price.

### Staking

Writing permissions to a blockchain’s transaction history are
administered by the access to private keys, which are connected to
public addresses controlling cryptocurrencies. However, only using
private keys does not protect the blockchain from users trying to spend
their holdings twice, also known as double-spend attacks. To protect
itself from these attacks, all blockchains implement some form of
consensus process that enables the network to reach consensus regarding
transaction validity. In order to ensure that users do not corrupt the
consensus process, participation must come with a cost. For example, the Bitcoin network consumes electricity,
in a process called Proof-of-Work (PoW), in order to protect its
transaction history. Staking, or more formally Proof-of-Stake (PoS), is
another technology used by blockchains in order to maintain the
immutability of their transaction history. Participants of a blockchain
that implements staking can stake some of their holdings of the
network’s cryptocurrency in order to participate in the consensus
process. Those who stake and verify transactions in an honest manner are
rewarded with new cryptocurrencies, while those who verify transactions
that later are deemed invalid are penalized by loosing their stake.
Certain blockchains demand that staked cryptocurrencies are locked for a
certain time or that a certain amount of cryptocurrencies are staked,
while others allow the reward of staking to depend on the time the
holdings have been staked. The cost of staking is therefore an
alternative cost, i.e., the cost incurred due to not being able to
invest in other investments with higher return. An index that includes
return due to staking forces investors who seek to track the index to
stake some of their assets. This creates more complexity and, for that
reason, the BlockchainX indices do not include returns due to staking.
However, specific purpose indices can be created for clients where
staking revenue is included.

### Airdrops
Airdrops occur when a blockchain, or a part of a blockchain, decides to
distribute cryptocurrencies, free of charge, to either their or a
different blockhain’s users. They are most often performed in order to
boost network activity or to reward long-term users. Airdrops can come
unannounced or they can be disclosed beforehand. Established blockchains
that want to reward old users or boost network activity tend to not
announce airdrops, while new networks often announce their airdrops due
to marketing reasons. Airdrops often come with a need to perform some
tasks in order to obtain the free cryptocurrencies. This can include
holding the native asset at a specific date, having to perform a set of
transactions on the network, or participating in different surveys.
Given the unpredictable nature of airdrops, the BlockchainX indices do
not include their return.
Technically an airdrop is not different from a fork and for these reasons airdrops are treated in the same manner as forks.

Governance and control requirements for supervised contributors
===============================================================

Oversight function
------------------

Vinter Capital has, according to Article 5(1) of the BMR, established a
permanent and effective oversight function for all aspects of the
provision of benchmarks in the form of an index committee. The members
of the oversight function are selected and assured to have, in their
entirety, the necessary skills, knowledge and expertise. No member of
the committee has been convicted of financial service related offences.
The BlockchainX indices are not based on contributors and are thus not
subject to contributor-related conflict risks. The oversight function is
embedded within the Vinter Capital’s organizational structure to allow
it to effectively challenge the management body’s decision. The
oversight function has the power to act independently of the
administrator, where the Regulation requires it to report to the
relevant competent authority any misconduct by contributors or
administrators and any anomalous or suspicious input data according to
Article 5(3) point (i) of the BMR. The oversight function continuously
assures that the administrator can operate exclusively using readily
accessible data.

The oversight function shall operate with integrity and shall have the
following responsibilities, which shall be adjusted by Vinter Capital
based on the complexity, use and vulnerability of the benchmark:

1.  reviewing the benchmark’s definition and methodology annually which
    includes, but is not limited to, exchange and constituent criteria,
    ranking procedures and weighting schemes, data providers and
    standardized evalutaion procedures.

2.  overseeing any changes to the benchmark methodology and being able
    to request the administrator to consult on such changes.

3.  overseeing the administrator’s control framework, the management and
    operation of the benchmark. The control framework contains
    provisions requiring periodic review of the process for contributing
    input data, effective oversight of the same, and policy on
    whistleblowing, including appropriate safeguards for
    whistle-blowers.

    As of today, Vinter Capital considers all of its data used for the
    benchmark as readily available and, therefore, not in need of a code
    of conduct referred to in Article 15 of the BMR.

4.  reviewing and approving procedures for cessation of the benchmark,
    including any consultation about a cessation.

5.  overseeing any third party involved in the provision of the
    benchmark, including calculation or dissemination agents.

6.  assessing internal and external audits or reviews, and monitoring
    the implementation of identified remedial actions.

7.  if the benchmark at any time becomes based on input data from
    contributors, monitoring the input data and contributors and the
    actions of the administrator in challenging or validating
    contributions of input data.

8.  if the benchmark at any time becomes based on input data from
    contributors, taking effective measures in respect of any breaches
    of the code of conduct referred to in Article 15.

9.  reporting to the relevant competent authorities any misconduct by
    contributors, where the benchmark is based on input data from them,
    or administrators, of which the oversight function becomes aware,
    and any anomalous or suspicious input data.

### Constitution of the oversight function

Vinter Capital will have clear criteria to select members and observers
including the evaluation of their expertise and skills (but without
publicly disclosing their identity), rules for the meetings of the
oversight function and on the participation of staff members therein,
the selection of the contact person for the management body and on the
interaction with it and arrangements to ensure confidentiality. Vinter
Capital will establish procedures to manage the conflicts of interests
which may arise due to competing interests of committee members. This
list covers the disclosure of conflicts of interest of members of the
oversight function, limitations and removal of voting rights from
conflicted members as well as the exclusion of members from discussions
where they could be conflicted. Furthermore, these procedures forbid
members to sit on oversight functions of more than one administrator.

Changes
-------

The procedures for consulting on any proposed material change in Vinter
Capital’s methodology as benchmark administrator and the rationale for
such changes are included below. This includes a definition of what
constitutes a material change and the circumstances in which Vinter
Capital is to notify users of any such changes. The procedures required
regarding proposed material changes provides for advance notice, with a
clear time frame, that gives the opportunity to analyse and comment upon
the impact of such proposed material changes. Those comments and Vinter
Capital’s response to those comments are made accessible after any
consultation, except where confidentiality has been requested by the
originator of the comments.

### Material change

ESMA allows administrators to define material change and determine the
practical aspects of the consultation procedure at their discretion. A
material change of a benchmark is any change to the index methodology
that would lead to a substantial change in index trajectory.

### Consultation

Vinter Capital’s Compliance Department will review any changes to this
methodology. The Compliance Department, as well as the independent
Oversight Function, has the power to, at any time, request further
explanations and information regarding those changes. The Compliance
Department will analyse the possible changes with respect to their
accuracy, reliability, verifiability, clarity, robustness, transparency,
validity and integrity. The Compliance Department will produce a review
statement, wherein the compliance of the proposed changes is determined.
The statement will be sent to Vinter Capital’s operative department and
archived. Material changes must, in addition to being approved by Vinter
Capital’s Compliance Department, be approved by the independent
Oversight Function in order to be enforced and implemented.

### Notice

All material changes are subject to an advance notice published by
Vinter Capital. The notice will be sent to users as well as published 60
days prior to the change and will include a clear time frame. Vinter
Capital may apply a shorter notice at its own discretion if the affected
index is not being used nor is licensed to any third party using it for
its financial product(s). All recipients of the notice will be given the
opportunity to comment on the proposed change(s). All comments will be
published by Vinter Capital except when the commenting party explicitly
has requested confidentiality.

### Discretion

Vinter Capital has established clear rules identifying how and when
discretion may be exercised in the determination of benchmarks. Vinter
Capital may at its own discretion change input data if it can not be
derived from:

1.  a computational scheme using readily available data, or data
    contributed under a code of conduct, and that are approved by the
    oversight function or to be considered of the same standard as those
    approved by the oversight function or another assessor independent
    scheme.

2.  a designated assessor or a group of designated assessors whose
    expertise, excperience as well as characters have been reviewed by
    the oversight function.

Compliance statement
====================

Vinter Capital is compliant with Article 25 and 26 of the BMR and will
therefore not publish a compliance statement explaining its reason for
non-compliance.

Appendix
========

Index tickers
-------------

  **Constituents**   **Weighting**   **Denomination**   **Ticker**
  ------------------ --------------- ------------------ ------------
  10                 Market cap.     SEK                BL10M-S
  10                 Equal           SEK                BL10E-S
  5                  Market cap.     SEK                BL5M-S
  5                  Equal           SEK                BL5E-S
  10                 Market cap.     EUR                BL10M-E
  10                 Equal           EUR                BL10E-E
  5                  Market cap.     EUR                BL5M-E
  5                  Equal           EUR                BL5E-E
  10                 Market cap.     USD                BL10M-U
  10                 Equal           USD                BL10E-U
  5                  Market cap.     USD                BL5M-U
  5                  Equal           USD                BL5E-U

  : Ticker naming convention for the BlockchainX
  indexes.[]{data-label="ticker-table"}

Changes to the index methodology
--------------------------------

This table contains all changes to the index methodology after 0180101,
when the European Bench- mark Regulation became effective.

  **Date**   **Version**   **Section**              **Change**
  ---------- ------------- ------------------------ ----------------------------------------------
  20181220   0.2           3.4 Circulating supply   Computation scheme
  20181220   0.2           4.7.1 Forks              Criteria for selected contentious hard forks
  20181220   0.2           4.7.1 Forks

  : Changes to the index methodology[]{data-label="changes-table"}

[^1]: [www.ecb.europa.eu/stats/policy\_and\_exchange\_rates/euro\_reference\_exchange\_rates](www.ecb.europa.eu/stats/policy_and_exchange_rates/euro_reference_exchange_rates)
