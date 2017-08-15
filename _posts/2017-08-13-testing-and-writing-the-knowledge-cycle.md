---
title: Testing and Writing - the Knowledge Cycle
---

{:center: style="text-align: center"}
"Clear thinking becomes clear writing" - William Zinsser <u>On Writing Well</u>
{:center}

One of the main components of software testing is knowledge management. This knowledge is learned prior to, during, and after testing actions. Therefore, learning is another essential aspect of software testing. Learning is the process by which one obtains knowledge. Writing can be seen as a process that forces the author to struggle with and eventually clearly understand the information and knowledge that is being written about. As the above quote stresses - clear thinking is a necessary and sufficient pre-requisite for clear writing. When writing, a writer is forced to clearly think about the topic under study. Cloudy writing is a smell that generally indicates missing or incomplete knowledge-understanding. So, writing testing knowledge in code or in a document not only saves this knowledge for later use, it provides a litmus test of whether the tester truly understands the application and tests they are using.

So where does this knowledge cycle start?

Information, and therefore knowledge, which is also referred to as information in context, is obtained by asking, and then answering questions raised. There are three main classes of questions that can be raised:

* The known: questions I can raise and answer
* The unknown: questions I can raise but not yet answer
* The unknown unknown: questions I do not and cannot raise

 All software testing projects involve these three types of knowledge. We start with the known. Address the unknown, and as the project moves forward, more questions are raised and answered. These last set of questions are examples of ones that start as unknown/unknowns.

 When a project starts, especially if it is a greenfield project, our knowledge horizon is small. As more is learned, more is seen, and therefore questions that did not even exist in the beginning are raised, researched, and answered. Once answered they then need to be recorded in software code for automated tests or in a more traditional technical document for later manual testing. This writing process also forces a more complete understanding of the knowledge being used.  Whether attempting to record the new testing knowledge as software code or prose, this step forces the tester to think clearly about the test knowledge. In my experience, unclear writing is easier to spot than unclear test knowledge especially when it only lives in the tester's mind.

 Different types of testing help to broaden a tester's horizon. Take exploratory and automated regression testing as examples. Exploratory testing helps to move our knowledge horizon forward by raising new questions and finding answers. In other words it takes the unknown unknown and transforms these questions into the unknown and eventually to the known.  

 On a somewhat opposite pole comes automated regression testing. This type of testing takes known knowns and ensures that this knowledge is still true even after changes to the source code of the application under test.

 All tests start as exploratory. Whether using code or manual testing, a tester must start with exploration. These exploratory "experiments" provide a ground of reference and are often derived from software requirement acceptance criteria. For example, take the requirement: a password must be greater than 5 characters.

 One must explore how the application operates when a 4 character password is used. Or a 10 character password. Or a password of all spaces. Note, our acceptance criteria said nothing of types of characters enforced. There may be another criteria that covers this, or we may have stumbled upon a missing requirement. Regardless, each step in testing generates knew knowledge that dictates our next action.

 Each new piece of knowledge needs to be recorded in some way for example: by writing automated tests or by creating manual test artifacts. New knowledge is gathered, written, and then applied as a starting point for another question to be asked, answered, and written. The ability to create technical documentation artifacts is critical in this process. Whether a traditional technical document or something like Cucumber is used, testing knowledge must be kept in a learnable state as to help the tester and/or their team learn from their past held knowledge.

 In testing, as the above quote reminds us, clear thinking is needed for clear writing. Writing is the canary in the testing lab. Unclear writing indicates only partial knowledge, where as clear writing indicates understanding. In other words, clear writing is needed for effective knowledge management. I will leave you with a quote by Flannery O'Connor that sums up these ideas.

{:center: style="text-align: center"}
"I write because I don't know what I think until I read what I say."
{:center}
