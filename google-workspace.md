1. Summary

This complaint documents a deceptive billing dark pattern utilized by Google Workspace to artificially capture uncompensated consumer liquidity. The target entity advertises a service with an explicit, immediate cost of "$0.00". However, the checkout architecture enforces a mandatory $10.00 capital hold to complete the "$0.00" transaction.

This mechanism misrepresents the true cost of entry, violates the FTC's guidelines on deceptive pricing, and levies a severe operational penalty on consumers who utilize independent or prepaid financial infrastructure.

2. The Structural Contradiction (The Dark Pattern)

As demonstrated in the attached evidentiary screenshot (google-workspace-highlight.png), the Google Workspace checkout interface relies on explicit cognitive dissonance:

The Advertised Price: The interface prominently features badges stating "No cost for 14 days" and an Order Summary explicitly declaring "Due Today: $0.00 + tax".

The Hidden Capital Requirement: Subordinated beneath the primary pricing display, in smaller text under the payment method, the interface states: "A temporary $10.00 authorization will be placed on your card... typically removed within a week."

A transaction cannot mathematically or legally be "Due Today: $0.00" if the system technically prohibits the user from proceeding without first surrendering access to $10.00 of liquid capital. Disguising a mandatory $10 entry fee as a background security check is a textbook dark pattern designed to obscure the true cost of the "free" tier.

3. The Institutional Liquidity Trap

This architecture generates a massive, uncompensated financial advantage for the target entity. By demanding a $10.00 authorization hold across millions of user sign-ups, the institution effectively forces consumers to provide a zero-interest micro-loan.

While the individual amount is small, aggregating these 7-day holds allows the corporation to float millions of dollars of user capital at no cost to themselves, while the consumer bears the entirely of the opportunity cost and financial restriction.

4. The Operational Friction Tax

Beyond the financial deception, this dark pattern actively discriminates against and penalizes users who operate outside traditional credit systems.

For consumers relying on sovereign infrastructure, prepaid debit cards, or privacy-focused virtual "burner" cards to protect their data, a $10.00 authorization on a $0.00 balance triggers an immediate structural failure. To bypass this "free" barrier, a user is forced to physically travel, expend time, and reload capital onto a prepaid card solely to satisfy the institution's arbitrary authorization script.

This constitutes a physical and temporal tax imposed on consumers simply for attempting to access a service exactly as it was advertised ("$0.00 Due Today").

5. Requested Regulatory Action

We request that the FTC's Bureau of Consumer Protection investigate this specific checkout flow as a violation of the FTC Act regarding deceptive pricing and "junk fee" mandates.

Specifically, we request regulatory enforcement requiring the entity to:

Cease the practice of requiring capital authorizations that exceed the explicitly stated "Due Today" total.

If a $10.00 hold is functionally required, it must be legally advertised as "Requires $10 Deposit," rather than misleadingly presented as a $0.00 transaction.

The central accountability principle is this: Institutional risk mitigation cannot be covertly financed by deceptive consumer liquidity traps.

---

The incriminating screenshots and report confirmation are available at https://substr8games.github.io/google-workspace.zip