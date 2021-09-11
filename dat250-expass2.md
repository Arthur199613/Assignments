# Experiment 1

# 1.Technical Problems with Installation and Use of JPA

There weren't many significant issues with use and installation of JPA. One of the glaring issues was having IntelliJ Community and not IntelliJ Ultimate which had database
support, but it was resolved after asking my classmates.

# 2.Link to Code

* Experiment 1: https://github.com/Arthur199613/Experiment1ToDo
* Experiment 2: https://github.com/Arthur199613/BankingApp1

# 3.How the Database Tables were Inspected and What Tables were Created

The experiment 1 database was viewed without many problems, everything appeared as it was supposed to. The problem came in the latter part of the assignment, even after having
seemingly wrote the correct code logically I was not able to get any sort of output to try and see how thbe database works.

<pre><code>Exception in thread "main" java.lang.IllegalArgumentException: Object: Pincode(id=null, pincodeNum=null, count=2) is not a known Entity type.
	at org.eclipse.persistence.internal.sessions.UnitOfWorkImpl.registerNewObjectForPersist(UnitOfWorkImpl.java:4328)
	at org.eclipse.persistence.internal.jpa.EntityManagerImpl.persist(EntityManagerImpl.java:601)
	at Main.main(Main.java:23)</code></pre>

# 4.Unsolved Issues

As mentioned by heading #3, I'm still yet to get the tables working as I'm not sure what the cause of the error is.
