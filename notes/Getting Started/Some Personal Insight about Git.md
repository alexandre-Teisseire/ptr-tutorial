# Git and VCSs in general

## Why git over Mercurial or even Subversion ?
That's the first question that came to my mind when i first looked into VCSs. Hence, i wasnt aware
that the concept of distributed version control wasnt popular before Linus Torvald came with Git.

Distributed revision control systems (DVCS) takes a peer-to-peer approach to version control, as opposed
to the client–server approach of centralized systems.

### Advantages of DVCS (compared with centralized systems) include:

- (6*) Allows users to work productively when not connected to a network.

- (5) Common operations (such as commits, viewing history, and reverting changes) are faster for DVCS, because there is no need to communicate with a central server. With DVCS, communication is only necessary when sharing changes among other peers.

- (7) Allows private work, so users can use their changes even for early drafts they do not want to publish.

- (1) Working copies effectively function as remote backups, which avoids relying on one physical machine as a single point of failure.

- (3) Allows various development models to be used, such as using development branches or a Commander/Lieutenant model.

- (2) Permits centralized control of the "release version" of the project

- (4) On FOSS software projects it is much easier to create a project fork from a project that is stalled because of leadership conflicts   ordesign disagreements.

(source Wikipedia besides the ranking)

\* : It becomes less and less a problem with the outbreak of 4g networks.

### Disadvantages of DVCS (compared with centralized systems) include:

- (2) Initial checkout of a repository is slower as compared to checkout in a centralized version control system, because all branches  and revision history are copied to the local machine by default.

- (1) The lack of locking mechanisms that is part of most centralized VCS and still plays an important role when it comes to non-mergeable binary files such as graphic assets.

- (3) Additional storage required for every user to have a complete copy of the complete codebase history.

(source Wikipedia besides the ranking)