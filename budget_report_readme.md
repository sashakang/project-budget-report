# TODO

1. ~~prod АСФР-017594 missing from `prods`~~  
2. Get quantities from the order and from job tickets. Use it to identify completed jobs in the report and to calculate BCWP. The notion here is that if the job is incomplete not BCWP can be computed. Or maybe it can be computed proportionally to the completion ratio. Something like that.
3. Use prod status to show and to select base to measure budget deviation  
4. find production start and finish dates. Assume linear target. Build earned value chart (see ticket description)  
5. extract order No to a variable  
6. dockerize, run as a service. Will need timestamp for this  