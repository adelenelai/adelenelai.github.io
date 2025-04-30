# Working with COCONUT DB using RDKit - sanitising Natural Product molecules
###  Some NPs cannot be sanitised

COCONUT DB is the largest open collection of natural products, developed by [Sorokina et al](https://doi.org/10.1186/s13321-020-00478-9).

In this notebook I will show the first steps of working with COCONUT DB using RDKit.

I encountered some issues, so maybe this post might be helpful for others in the future.

(Overall, this was also a lesson when working with Suppliers to use a 'context manager' in the future, as discussed [here](https://www.rdkit.org/docs/GettingStartedInPython.html).)

To start, I downloaded the Canonical SMILES .smi file from the [COCONUT website](https://coconut.naturalproducts.net/download) (Jan 2022 version).


{% gist b3579d3e02a10a330adae2f0818df137  %}
