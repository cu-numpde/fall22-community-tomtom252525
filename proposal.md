# Community Software Analysis Proposal
Please edit this file and push to your repository.

## Software: OpenFOAM

OpenFOAM is an open source Computational Fluid Dynamics (CFD) code used in academia and industry for problems ranging from solid mechanics to fluid flows of varying complexity. It was created on 2004 and is managed by OpenCFD with the mission of providing a highly functional, freely available, and open source CFD software.

### Stats

| Description | Your answer |
|---------|-----------|
| Repository URL |  https://github.com/OpenFOAM/OpenFOAM-dev  |
| Main/documentation website |  https://openfoam.org/resources/  |
| Year project was started |  Dec 2004 |
| Number of contributors in the past year | `git shortlog -se --since=2021-10-01` -> 4 |
| Number of contributors in the lifetime of the project | 11 |
| Number of distinct affiliations | 5-10 "Organizations Signing the contributor agreement" |
| Where do development discussions take place? | Mailing list, issue tracking system (https://bugs.openfoam.org/view_all_bug
_page.php)  |
| Typical number of emails/comments per week? |  9 issue updates on the above link per week |
| Typical number of commits per week? | 25 (a lot) |
| Typical commit size | `git log --shortstat` shows anywhere from 1 to 180 insertions/deletions per commit |
| How does the project accept contributions? | pull requests  |
| Does the project have an automated test suite? | yes? it has a test folder but don't understand what's in it |
| Does the project use continuous integration? | sortof - they have a dev version updated annually while another version is updated continually |
| Are any legal/licensing steps required to contribute? | Yes -> explained below |

### Install and run

Check the following boxes when complete or add a note below if you
encountered a problem.

- [-] I have installed the software
- [ ] I have run at least one example
- [ ] I have run the test suite
- [ ] The test suite passes

### Notes/concerns/risks

Please comment on any anomalies or known risks to following this
project, if you were unable to answer any questions above, or
otherwise have concerns about the appropriateness of the software.  If
the project requires a contributor license agreement or other
procedural steps, please explain here.  "None at this time" is
acceptable for this question.

Legal: Once a contribution is made, the contributor has to sign the OpenFOAM Foundation Contributor Agreement, which essentially transfers ownership of the code to OpenFOAM so they can take legal action against those who infringe the OpenFOAM licence (GNU General Public License).

Note: I was unable to find a place where development discussions are had. I simply found the issue tracking system. This may make sense with how few contributers there are, as I could imagine they communicate directly.

Note2: I have the repo cloned, but my lack of experience is making it hard to complete the rest of this. will try again tomorrow.

#### Note on copyright
Students retain copyright on any work done in completion of a CU
course, so you are authorized to sign a [contributor license
agreement (CLA)](https://en.wikipedia.org/wiki/Contributor_License_Agreement),
affirm a [developer's certificate of
origin (DCO)](https://en.wikipedia.org/wiki/Developer_Certificate_of_Origin),
etc.  If you have concerns about this, please note them and/or reach
out to Jed directly.
