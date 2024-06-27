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

2. Investor C wishes to invest only in S1 and S2, so weight w3 = 0. For weights w1 = -0.5, -0.4, ..., +1.5 and corresponding weight w2, tabulate expected portfolio return mu and standard deviation sigma. Then plot these as points in a sigma-mu diagram.

3. Investor D wishes to invest only in S1 and S3, so weight w2 = 0. For weights w1 = -0.5, -0.4, ..., +1.5 and corresponding weight w3, tabulate expected portfolio return mu and standard deviation sigma. Then plot these as points in a sigma-mu diagram.

## options-pricing
Consider the 3-period binomial model with a risk-free asset A with A(0) = 20, interest rate r = 0.076 and a stock S with S(0) = 10, "up" return u = 0.17 and "down" return d so that (1+d)(1+u) = 1.

We consider an American put option with STRIKE = 10.751.

1. Compute the intrinsic value process G(0), ..., G(3).

2. Investor A owns this option and decides to exercise it immediately after the stock price made an "up" movement (but only if the intrinsic value is nonnegative); or, if it has not been exercised yet, at time 3 (but only if the intrinsic value is nonnegative). Determine the stopping time that describes this exercise policy. Determine the resulting cash flow process and the present value (time 0 value) of the cash flow process as a random variable. Then find the fair price (according to martingale pricing) of this cash flow process at time 0.

3. Investor B owns this option and decides to exercise it according to the European exercise rule: at time 3 (but only if the intrinsic value is nonnegative). Determine the resulting cash flow process and the present value (time 0 value) of the cash flow process as a random variable. Then find the fair price (according to martingale pricing) of this cash flow process at time 0.

4. Investor C owns this option and wishes to exercise it optimally. Determine the stopping time that describes the optimal exercise, the non-discounted price process, and the cash flow process.

Your personal derivative security D has the following continuous piecewise linear payoff function D(1), depending on the price S(1) of the underlying stock S.

If 0 <= S(1) <= 30, then D(1) = 0.

On the interval 30 <= S(1) <= 4X, the payoff D(1) increases linearly until for S(1) = 4X it reaches the value 5Y.

On the interval 4X <= S(1) <= 8Z, the payoff D(1) decreases linearly until for S(1) = 8Z it becomes 0.

For S(1) >= 8Z, D(1) remains 0.

1. Plot this function and determine expressions for D(1) as a function of S(1) on each of the two middle pieces.

2. Determine if it is possible to replicate this payoff function D(1) using a portfolio of only the stock S and a risk-free asset A of price A(1)=77. If yes, show a replicating portfolio; if no, explain why not.

3. Determine if it is possible to replicate this payoff function using a portfolio consisting only of finitely many call options. If yes, show a replicating portfolio; if no, explain why not.

4. Find a portfolio that replicates this payoff function that contains at least one put option and at least one call option but not the stock S. It is allowed to use the risk-free asset A in the portfolio.

5. Now assume that S(1) can only take two values: S^u(1) = 62 and S^d(1) = 33, and repeat question 2 above.

## investment-strats
Consider the 3-period binomial model with a risk-free asset A with A(0) = 20, interest rate r = 0.056 and a stock S with S(0) = 10, "up" factor u = 0.101 and a "down" factor d = 0.027.

1. Compute the (path-independent) stock price process S(0), S(1), S(2), S(3).

2. Compute the discounted stock price process S̃(0), S̃(1), S̃(2), S̃(3). 

3. Investor A estimates that the probability of "up" equals p = 0.9Y. Compute 𝔼2[S̃(3)], that is, the conditional expectation of S̃(3) given the information about the first two coin tosses as a random variable. Then compute 𝔼1[S̃(3)].

4. Compute the risk-neutral probability p＊ and the conditional expectations 𝔼2＊[S̃(3)] and 𝔼1＊[S̃(3)].

5. Investor B estimates that the probability of "up" equals p = 0.6ZZZ. He likes to take a nap from time 1 to time 2 and therefore fails to observe the second coin toss; but he wakes up in time to observe the third coin toss. Determine the sigma-algebra 𝓕1 and the sigma-algebra 𝓕1X3 that model the information available to Investor B at time 1 and time 3, respectively. Then determine 𝔼[ S̃(3) | 𝓕1X3 ], that is, the conditional expectation of S̃(3) conditioned on 𝓕1X3. This should be a random variable measurable in the sigma-algebra 𝓕1X3.

Consider a European put option D on the underlying S with expiration date 3 and strike price 12.75.

1. Determine the payoff D(3) of the option at expiration as a random variable.

2. Compute the non-discounted price process D(0), D(1), D(2), D(3) of the option as a (path-independent) stochastic process, and determine the investment strategy that replicates the option as a (path-independent) stochastic process.

3. Is it possible to replicate the option using a static investment strategy instead?

