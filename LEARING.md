Following this for Our Purpose:
        https://www.cedarpolicy.com/en/tutorial/rbac
    
What if there is a conflict: 
   https://docs.cedarpolicy.com/syntax-policy.html

    After all policies in the policy store are evaluated, the results are combined as follows:
    If at least one matching policy results in Allow and there are exactly zero policies that result in Deny, then the overall result of the evaluation is Allow.
    If at least one matching policy results in Deny or if there are exactly zero policies that result in Allow, then the overall result of the evaluation is Deny.

    So Deny if there is a conflict.

