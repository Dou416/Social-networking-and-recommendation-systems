# Social-networking-and-recommendation-systems
Assigment 4 for MG-GY 8401 Programming for Business Intelligence and Analytics 

Facebook suggests people you may be (or should be) friends with. Netflix suggests movies you might like. Amazon suggests products to buy. These are all the work of recommendation systems. In this assignment, you will learn one simple way to make such suggestions, called collaborative filtering. The actual algorithms used by these companies are closely guarded trade secrets.  

A computer system that makes suggestions is called a recommender system. As background, there are two general approaches: collaborative filtering and content-based filtering. 

  • Collaborative filtering says that, if your past behavior/preferences were like some other user's, then your future behavior may be as well. As a concrete example, suppose that you like John, Paul, and George, and other people like John, Paul, George, and Ringo. Then it stands to reason that you will like Ringo as well, even if you had never previously heard of him. The recommender system does not have to understand anything about what “John”, “Paul”, “George”, and “Ringo” are — they could even be brands of toilet paper, and the algorithm would work identically. 
  • Content-based filtering considers the characteristics of the things you like, and it recommends similar sorts of things. For instance, if you like “Billie Jean”, “Crazy Train”, and “Don't Stop the Music”, then you might like other songs in the key of F-sharp minor, such as Rachmaninoff's “Piano Concerto No. 1”, even if no one else has ever had that particular set of favorite songs before. 

This assignment required us to write a program that reads Facebook data and makes friend recommendations. 
