# Financial Mathematics
## stock-pricing
We consider the 3-period binomial model with a risk-free asset A with A(0) = 20, interest rate r = 0.076 and a stock S with S(0) = 10, "up" return u = 0.17 and "down" return d so that (1+d)(1+u) = 1.

Consider a European-style arithmetic mean (Asian) call option D on the underlying S with expiration date 3 and strike price 9.75. The payoff of such an option is defined as max(arithmetic mean(S(0), ..., S(3)) - strike price, 0). 

1. Compute the stock price process S(0), S(1), S(2), S(3) and the sum-so-far process Y(0)=S(0), Y(1)=S(0)+S(1), Y(2)=S(0)+...+S(2), Y(3)=S(0)+...+S(3); and the risk-neutral probability p＊

2. Determine the payoff D(3) of the option at expiration for every possible states at time 3, i.e., pair of values that the pair (S(3), Y(3)) of random variables takes.

3. Compute the non-discounted price D(2) of the option for all states at time 2, i.e., pairs (S(2), Y(2)). No need to compute the replicating investment strategy.

4. Compute the non-discounted price D(1) of the option for all pairs (S(1), Y(1)). No need to compute the replicating investment strategy.

5. Compute the non-discounted price D(0) of the option. No need to compute the replicating investment strategy.

Now, an American call option with expiration date 3 gives the owner the right but not obligation to buy stock at the strike price STRIKE. In contrast to the European call, the owner of the option has the right to exercise the option at any one of the times 0, 1, 2, 3. We consider a call with STRIKE = 10.75.

1. Compute the non-discounted stock price process S(0), S(1), S(2), S(3).

2. The intrinsic value process G(0), ..., G(3) is defined as G(t) = S(t) – STRIKE. Compute it.

3. Investor A owns this option and decides to exercise it at the following times: Immediately after observing ω1=u (that is, at time 1); immediately after observing ω1ω2=du (that is, at time 2); after observing ω1ω2ω3=ddu (that is, at time 3); otherwise, he lets the option expire. Determine the resulting cash flow process and price it.

4. Investor B owns this option and wishes to exercise it optimally. Determine the stopping time that describes the optimal exercise, the non-discounted price process, and the cash flow process.

Consider a 1-period model and three securities: S1, S2, S3 with expected returns 0.046, 0.057, 0.06, standard deviations 0.027, 0.02, 0.056 and correlation coefficients ρ_12=0.87 (but if Y=9, use ρ_12=0.79), ρ_13=-0.27, ρ_23=0.17

1. Determine the covariance matrix.

2. Investor A wishes to invest only in S1 and S2, so weight w3 = 0. For weights w1 = -0.5, -0.4, ..., +1.5 and corresponding weight w2, tabulate expected portfolio return mu and standard deviation sigma. Then plot these as points in a sigma-mu diagram.

3. Investor B wishes to invest only in S1 and S3, so weight w2 = 0. For weights w1 = -0.5, -0.4, ..., +1.5 and corresponding weight w3, tabulate expected portfolio return mu and standard deviation sigma. Then plot these as points in a sigma-mu diagram.
