.. hydrogenesis documentation master file, created by
   sphinx-quickstart on Thu Feb 13 12:31:03 2020.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

Hydrogenesis
========================================

.. toctree::
   :maxdepth: 2
   :caption: Contents:

Hydrogenesis is an object-oriented, high-level language for implementing DPROGs, which are programs hosted on the Fluidity blockchain and used for a number of purposes related to the Fluidity blockchain, Flow, and any other coins hosted by Fluidity.

Hydrogenesis was influenced by Python and JavaScript. All Hydrogenesis programs are hosted by the DPROG address and validated via the blockchain. Programs are stored in wallet accounts to detect changes to the program hosted by the DPROG address, and enough invalidations can invalidate the DPROG address license from the Fluidity blockchain.

With Hydrogenesis you can create DPROGs for uses such as digital currency, decentralized exchange, voting, crowdfunding, blind auctions, games, and an assortment of other programs.

Hydrogenesis does not allow for any calls from internet data due to the nature of the blockchain and the existence of offline (cold) wallets. The Fluidity blockchain therefore allows DPROGs to invoke other DPROGs, which may be constantly fed data by users that submit the data to the DPROG address through the blockchain.

When deploying DPROGs, you should use the latest released version of Hydrogenesis. This is because breaking changes as well as new features and bug fixes are introduced regularly.
