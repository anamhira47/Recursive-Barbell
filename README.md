# Recursive-Barbell
Recursive Barbell Trading Strategy, based on fractal risk-taking. Inspired by the barbell strategy outlined by Nassim Taleb in his book series Incerto.

The Recursive Barbell Trading Strategy works by allocating 90% of funds being invested to a "safe" allocation and 10% to a riskier portion. Inside that 10%, 90% will be allocated to a relatively safer investment and 10% to an even riskier portion. This will continue in a fractal sense recursively until the ceiling of the nth term is too small of an amount to divide further (set by user). 

When inputting strategies under the framework of a recursive barbell one should increase the risk of the instrument exponentially, as to leverage positive black swan profits. Doing so takes full advantage of the algorithm. 

This will most likely lead to many small losses. However the winnings when they do happen will be very large due to the exponential risk curve. It also limits major risk as there is a very small percentage of funds being allocated to the riskier investment. This algorithm provides a much better solution to investors who want to win from riskier investments but do not want to have such huge losses. 

The bot will be built utilizing a multitude of AWS services to create a highly available and fault tolerant system with minimal operational overhead.

This will be represented using a cloudformation stack template.
