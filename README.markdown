A simulated system of small business equity, as described [by Steve Randy Waldman, aka @interfluidity.](http://www.interfluidity.com/v2/257.html)

I currently plan to use the [FMS package](http://packages.python.org/fms/) to simulate the purchase of future dollars from businesses by investors, and the eventual maturation of that equity when it is realized as revenue. Some instructions are [here.](http://packages.python.org/fms/tutorial.html#running-the-experiment)

This is the simulation cycle I expect to implement: 

1. Create a list of businesses, each with an expected revenue stream and a risk factor.
2. Create a list of investors, each with a range of acceptable risk and a time horizon.
3. Offer dollar futures from all businesses to investors.
4. Allocate futures from businesses to investors through a simulated sale or auction
5. Generate one or two variables of economic context that all the businesses are subject to
6. Generate a revenue cycle for each business based on some pseudorandom variance from the economic background conditions
7. Calculate which dollars of revenue will become recouped futures
8. Repeat steps 5 through 7

Questions: 

+ Is there a secondary market?


