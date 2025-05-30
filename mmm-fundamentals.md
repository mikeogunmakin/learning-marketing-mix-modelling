
# 📘 Fundamentals of Marketing Mix Models (MMMs)

## ❓ What are MMMs?

Marketing Mix Models (MMMs) are statistical models used by marketers to measure the impact of various marketing activities (like TV, radio, digital, print, pricing, promotions, etc.) on key business outcomes such as sales, brand awareness, or customer acquisition.

## 🎯 Why are MMMs important?

Advertisers need to understand the effectiveness of their media spend in driving sales in order to optimise budget allocations.

However, tracking and attribution have become more difficult as privacy concerns have grown. Media mix models are a common and widely used approach for understanding marketing effectiveness without compromising user privacy.

## ⚙️ How do MMMs work?

An MMM is usually built as a regression model, where sales (or another KPI) is the dependent variable, and marketing activities and control variables are the independent variables.

$$
Y_t = \beta_0 + \sum_{m=1}^{M} \beta_m \cdot f(X_{t,m}) + \sum_{c=1}^{C} \beta_c \cdot Z_{t,c} + \epsilon_t
$$

### 🔍 Explanation of Variables

- $$Y_t$$: Outcome variable at time $$t$$  
  _e.g. sales, conversions, or revenue_

- $$β₀$$: Intercept term  
  _The baseline level of the outcome when all inputs are zero_

- $$X_{t,m}$$: Media variable $$m$$ at time $$t$$  
  _e.g. spend on TV, search, or social media_

- $$f(X_{t,m})$$: Transformation function applied to media inputs  
  _Usually includes adstock (to model lagged effects) and saturation (to model diminishing returns)_

- $$βₘ$$: Coefficient for media variable $$m$$  
  _Represents the effectiveness or contribution of media channel m to the outcome_

- $$Z_{t,c}$$: Control variable $$c$$ at time $$t$$  
  _e.g. seasonality, holidays, pricing changes, competitor activity_

- $$β_c$$: Coefficient for control variable $$c$$  
  _Measures the impact of external or non-media factors_

- $$ε_t$$: Error term  
  _Captures noise or unexplained variation in the outcome variable_


## How are MMMs used in practice?

### 1. To Measure Marketing ROI (Marketing effectiveness)
They help determine which channels drive results, and how much return each channel brings relative to spend.

### 2. To Optimise Media Budgets (Budget Allocation Optimization)
MMMs inform budget allocation by identifying diminishing returns and optimal spend levels.

### 3. To Inform Strategic Planning (Business results Stimlulation)
By simulating “what-if” scenarios, MMMs allow teams to model the impact of different marketing strategies before implementing them.

### Example of MMM Outputs

![Diagram](learning-marketing-mix-modelling\images\examples-of-MMM-outputs.png) 



---

## 📚 References

- https://research.google/pubs/challenges-and-opportunities-in-media-mix-modeling/
- https://www.thinkwithgoogle.com/_qs/documents/18374/Marketing_Mix_Modeling_Guidebook.pdf
