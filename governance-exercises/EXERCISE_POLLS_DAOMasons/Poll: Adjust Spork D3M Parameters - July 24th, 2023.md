---
title: Adjust Spork D3M Parameters - July 24th, 2023
summary: Signal your support or opposition to adjusting the Spork DAI Direct Deposit Module (D3M) parameters.
discussion_link: https://github.com/makerdao/community/blob/master/governance-exercises/poll-exercise-01.md#reply-1
parameters:
    input_format: single-choice
    victory_conditions:
        - { type : plurality }
    result_display: single-vote-breakdown
version: v2.0.0
options:
   0: Abstain
   1: Yes
   2: No
start_date:  July 24th, 2023 T16:00:00
end_date: July 27th, 2023 16:00:00
---
# Poll: Adjust Spork D3M Parameters - July 24th, 2023

The Governance Facilitators have placed a Governance Poll into the [voting system](https://vote.makerdao.com/polling) on behalf of Spork Protocol. The community can vote in this poll to express support or opposition to using the Spork Direct Deposit DAI Module (D3M) with the listed parameters. This Governance [Poll](https://manual.makerdao.com/governance/governance-cycle/weekly-governance-cycle#weekly-governance-cycle-definitions-mip16c1) will be active for three days beginning on July 24th, 2023 at 16:00 UTC.

**This is a binary vote.**
- **You may vote for a single option.**
- **You should vote for the option which you prefer.**
- **If you would accept either option, you should vote 'Abstain'.**

## Review

There has been notable growth of Spork Protocol in recent months. To maintain the momentum and harness the expanding user base, several modifications to the protocol parameters are proposed. These changes aim to serve larger users better, encourage more deposits, and manage the increased demand. These proposals have gained the support of the stability scope facilitators, despite their recognition of slightly elevated risks. 

The community can vote in this poll to express support or opposition to making the following parameter changes to the Spork DAI Direct Deposit Module (D3M):
* Increase the DIRECT-Spork-DAI [Maximum Debt Ceiling(line)](https://manual.makerdao.com/module-index/module-dciam#maximum-debt-ceiling-line) from **50 million DAI** to **100 million DAI**.
* Increase the DIRECT-Spork-DAI [Target Available Debt(gap)](https://manual.makerdao.com/module-index/module-dciam#target-available-debt-gap) from **5 million DAI** to **15 million DAI**.
* Increase the DIRECT-Spork-DAI [Ceiling Increase Cooldown(ttl)](https://manual.makerdao.com/module-index/module-dciam#ceiling-increase-cooldown-ttl) from **28,800 seconds** (8 hours) to **86,400 seconds** (24 hours).
* Adjust Spork Protocol [DAI Deposit Rate](link-to-theoretical-parameter.fake) from **2%** to **2.5%**

Please review the discussion [thread]([$discussion_link](https://github.com/makerdao/community/blob/master/governance-exercises/poll-exercise-01.md#reply-1)) to help inform your position before voting. 

For more information regarding the DAI Direct Deposit Module (D3M) and how these parameters interact, check out the forum thread [here](https://forum.makerdao.com/t/discussion-direct-deposit-dai-module-d3m/7357).

## Outcomes

**If the votes for the 'Yes' option exceed the votes for the 'No' option then the following actions will be taken:**
* These parameter changes will be included in an upcoming Executive Vote.
* It is expected that this Executive Vote will take place within 30 days of this poll passing, absent external factors.
* If the Executive Vote passes, then these changes will become active in the Maker Protocol after the [GSM Pause Delay](https://manual.makerdao.com/parameter-index/core/param-gsm-pause-delay) has expired.

**If the votes for the 'No' option equal or exceed the votes for the 'Yes' option then no further action will be taken at this time.**

---

## Resources

If you are new to voting in the Maker Protocol, please see the [voting guide](https://manual.makerdao.com/governance/voting-in-makerdao/on-chain-governance) to learn how voting works.

Additional information about the Governance process can be found in the [Maker Operational Manual](https://manual.makerdao.com).

To add current and upcoming votes to your calendar, please see the [MakerDAO Governance Calendar](https://manual.makerdao.com/makerdao/calendars/governance-calendar).