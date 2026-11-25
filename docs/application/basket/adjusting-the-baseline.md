# Adjust the baseline

This is step 3 of the [basket steps](./basket-steps.md).

The baseline is the set of terms you propose to the providers. It is the starting point of the negotiation. You can only adjust the terms that the providers left negotiable: the other terms are fixed by the provider.

## Pricing

When the provider allows the price of the selected package to be negotiated (PRICE NEGOTIABLE tag), the pricing block is displayed and you can propose your own subscription pricing, billing period, setup fee, cost per API call and pricing description. The currency is set by the provider and cannot be changed. When the package has a fixed price (PRICE FIXED tag), the pricing block is not displayed.

<p><img src="../../images/basket-baseline-pricing.png" alt="Pricing" width="85%"></p>

## How it works

The other terms are displayed in a table. The "Common value" row applies to every offer in the basket. Each offer has its own row below, so that you can change a value for a single offer, for example when one provider needs a different duration.

An icon next to each value shows where it comes from: a link icon means the offer uses the common value, and an orange arrow means the value has been customized. Click on the orange arrow to go back to the common value. Under the common value, the **Apply to all** link applies it to every offer.

<p><img src="../../images/basket-baseline.png" alt="Adjust the baseline" width="85%"></p>

The terms you can adjust are:

- **Contract duration**: a number and a unit, such as 2 years.
- **Renewal mode**: "No renewal" or "Automatic renewal". With automatic renewal, you also enter a notice period for non-renewal, which sets how long before the end of the contract a party must give notice if it does not want to renew.
- **Time period**: the start date of the access. The end date is calculated from the contract duration and cannot be edited.
- **Count**: a usage policy that limits how many times the data can be used. If an offer does not have this policy, "Not applicable" is displayed.

Once the baseline is ready, click the **Continue** button to go to the last step: [Confirm & send](./basket-steps.md#step-4-confirm-send).