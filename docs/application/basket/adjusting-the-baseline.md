# Adjust the baseline

This is step 3 of the [basket steps](./basket-steps.md).

The baseline is the starting point of the negotiation. In this step, you set the values you propose to the providers for the terms of each offer. Some of these terms can be negotiated and others cannot: see [which terms are negotiable and which are not](#fixed-and-negotiable-terms).

For each offer, the page displays the terms you set. Contract duration and renewal mode are always displayed. The pricing, the time period and the count are displayed only when they apply to the offer: each section below explains when.


## How it works

The terms are displayed in a table. The "Common value" row applies to every offer in the basket. Each offer has its own row below, so that you can change a value for a single offer, for example when one provider needs a different duration.

An icon next to each value shows where it comes from: a link icon means the offer uses the common value, and an orange arrow means the value has been customized. Click on the orange arrow to go back to the common value. Under the common value, the **Apply to all** link applies it to every offer.

<p><img src="../../images/basket-baseline.png" alt="Adjust the baseline" width="85%"></p>

## Pricing

The provider decides if the price of a package can be negotiated. If it can, a pricing block is displayed: propose your own pricing there. If it cannot, the block is not displayed and the price of the package applies.

<p><img src="../../images/basket-baseline-pricing.png" alt="Pricing" width="85%"></p>

## Other terms

The table displays these terms:

- **Contract duration**: a number and a unit, such as 2 years.
- **Renewal mode**: "No renewal" or "Automatic renewal". With automatic renewal, you also enter a notice period for non-renewal, which sets how long before the end of the contract a party must give notice if it does not want to renew.
- **Time period**: the start date of the access. The end date is calculated from the contract duration and cannot be edited.
- **Count**: a usage policy that limits how many times the data can be used. If an offer does not have this policy, "Not applicable" is displayed.

Once the baseline is ready, click the **Continue** button to go to the last step: [Confirm & send](./basket-steps.md#step-4-confirm-send).

## Fixed and negotiable terms

!!! warning "What you can negotiate"

    | Term | Negotiable? |
    | --- | --- |
    | Pricing (subscription pricing, billing period, setup fee, cost per API call) | Only if the provider allows it |
    | Currency and pricing description | Never |
    | Contract duration, renewal mode and notice period | Yes, you set them in this step |
    | Usage policies (time period and count) | Yes, if the offer has them |
    | Resources | Never |
    | Service levels (SLA) | Never |
    | Commitments and penalties | Never |
    | Termination | Never |