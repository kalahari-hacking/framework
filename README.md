# Kalahari Hacking Society -- Penetration Testing Framework (Template)

## Step 1: ☢️ Attack Model

In order to secure a system, one should be aware of the 
__capabilities__ of the attackers, this is more important than trying
to consider all the possible specific attacks/exploits that can be
performed on the system. Once you have a detailed list of the 
capabilities of an attacker you can proceed to restrict these 
capabilities, this list of capabilities is the systems 
__Attack Model__. 

Likewise if an attacker is trying to exploit the system they should 
be aware of the attack model (their capabilities) and take advantage
of the capabilities that are unrestricted.

### Provable Security

In security, and especially in cryptography, precise definitions and 
proofs of security, or at least extensive, clear analysis, are 
necessary to ensure that a system is secure against arbitrary 
attacker strategies. This approach is usually referred to 
as __provable security__. As a penetration tester, you should always
ask yourself what proofs that this system/scheme is secure?

That said, one has to be very careful to __understand the limitations 
and pitfalls of proofs__, discussed in a series of papers by Koblitz 
and Menezes. Proofs of security often involve __simplifications__ and 
__assumptions__, even simplitying 'assumptions' known to be 
__incorrect__.

A proof of security is a powerful tool, but, like other power tools, 
should always be used carefully and correctly. Namely, we must fully 
understand the definitions, assumptions and simplifications, and 
never assume additional properties or applicability to scenarios 
where the assumptions do not hold.

### Risk and costs-benefit analysis

Security managers have to consider the __costs__ of deploying 
security mechanisms, against the __probability__ of an attack and the 
expected __damages__ from possible attacks, if the mechanisms are not 
deployed. __Risk analysis__ is an attempt to estimate the 
probabilities of occurrence of different attacks, and of the attacks 
being successful; and cost-benefit analysis uses these values, as 
well as the costs of deploying different security mechanisms, to 
decide which security mechanisms are worth deploying.
