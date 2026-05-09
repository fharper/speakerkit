# Sleep Better on Release Day: A Modern Testing Strategy for JavaScript SDKs and Components

With over 20 years in tech, Fred has seen firsthand what happens when testing is an afterthought: regressions that slip into production, release days that turn into firefighting sessions, and teams that lose confidence in their own deployments. Having also witnessed good testing processes and the difference is clear: it is not just talent, it is strategy.

Recently, Fred has been exploring the testing landscape at TinyMCE, and it represents a whole new level of complexity. Providing an Open Source core alongside premium plugins means testing goes beyond the code itself; it requires validating a massive, plugin-based architecture where open modules interact with commercial ones, all running across a wide variety of customer environments, browser versions, and browser types.

In this session, we will set aside standard "Testing Pyramid" theory and dive straight into the practical strategies required to validate such a complex ecosystem. The talk will cover the Integration Matrix (testing across frameworks and bundlers), the Timeline Strategy (using nightly builds to catch upstream browser engine breaks), and AI Models Interoperability, specifically, how to automate tests for Generative AI features where "exact match" assertions are simply not possible.
