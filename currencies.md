---
layout: page
title: Currencies
subtitle: Currency Specifications for Smart Contracts
navigation_weight: 2
permalink: /currencies/
---
                
All Digital Monetary Fund currencies are published on the Ethereum Live Block Chain as <em>ERC20 Smart Contracts</em>. 

The Ethereum Block Chain network was chosen because it is transparent, widely accepted and processes transactions very efficiently. Ethereum is a global, open-source, popular platform for decentralized applications. <a href="https://ethereum.org/">https://ethereum.org/</a> 

For consistancy and compatibility with the international financial payments system, our currencies mirror the <a href="https://www.iso.org/iso-4217-currency-codes.html">ISO Standard 4217 for currencies</a>

<strong>Rounding:</strong> Internally the Currencies have a standard 18 digits, although transfers use Bankers Rounding so that amounts behave like fiat currencies. Eg. transfers for 1USD are rounded to the nearest 2 decimal places or cent. Where the third fractional digit value is 5, the amount is rounded towards an even number.

<strong>Supply:</strong> The quantity of each currency varies according to market supply and demand for that DMF currency. To reduce supply a "burn" function is used, to increase supply a "mint" function is used. This enables each DMF to be backed close to 100% by underlying physical assets.<br /><br />
<strong>Escrow:</strong> An <em>Escrow</em> function allows transactions to be sent as Pending will in time be changed to Refunded (the customer received its refund) or Completed.

The Digital Monetary Fund project has built a new, smarter, financial system.
