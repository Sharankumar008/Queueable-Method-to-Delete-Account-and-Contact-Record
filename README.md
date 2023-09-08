# Queueable-Method-to-Delete-Account-and-Contact-Record

Create two queable job. One for deleting the contacts created last year and another one to delete the accounts created in last year.Create the Queueable jobs using system.enqueujob method.

//Anonymous window

QueueJobScheduler obj=new QueueJobScheduler();

obj.scheduleJobs();
