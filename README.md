# kubernaughty

This is a collection of documentation, how-tos, tools and other information on
debugging and identifying Kubernetes/container workload failures, performance
and reliability considerations.

Initially this investigation started as customer-reported failures at the DNS, 
networking and application levels, however through the analysis the actual causes
for these failures we due to severe resource saturation & contention, IO throttling, 
kernel panics, etc.

There are many gotchas, mud pits and blind spots running distributed systems,
and kubernetes is no different. Hopefully, this stuff helps you and your
team.

## Kubernaughty 1: IO saturation and throttling

 - [Part 1: Introduction & Issue summary](/docs/part1-introduction-and-problem-description.md)
 - [Part 2: Cluster Setup & Basic Monitoring](/docs/part2-basic-setup.md)
 - [Part 3: What's in the box?! (voiding the warranty)](/docs/part3-whats-in-the-box)
 - [Part 4: That's how you fail a container runtime](/docs/part-4-how-you-kill-a-container-runtime.md)

Feel free to use the bug tracker to ask questions or edits.
<!--stackedit_data:
eyJoaXN0b3J5IjpbLTkxNjAzNTEwMF19
-->