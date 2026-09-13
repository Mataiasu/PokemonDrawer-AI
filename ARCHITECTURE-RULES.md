# Architecture rules

## No God Files

Keep each source module cohesive and responsibility-focused. Do not accumulate unrelated UI, domain, persistence, networking, configuration, security or orchestration responsibilities in one file. Split modules when responsibilities or coupling become unrelated. Prefer explicit interfaces. Do not use a rigid line-count limit as the sole criterion. Generated/binary/vendor assets are exempt. New and modified source must preserve this rule.
