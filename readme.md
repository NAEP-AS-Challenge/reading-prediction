# ED.gov National Assessment of Educational Progress (NAEP) Automated Scoring Challenge

We are seeking seeking submissions of automated scoring models to score
constructed response items for the National Assessment of Educational
Progress's reading assessment. The purpose of the challenge is to help
NAEP determine the existing capabilities, accuracy metrics, the
underlying validity evidence of assigned scores, and costs and
efficiencies of using automated scoring with the NAEP reading assessment
items. The Challenge requires that submissions demonstrate
interpretability of models, provide score predictions using these
models, analyze models for potential bias based on student demographic
characteristics, and provide cost information for putting an automated
scoring system into operational use.

**CHALLENGE DETAILS**

TOTAL CASH PRIZES OFFERED: \$30,000 (maximum of $20,000 for first-place entries)\
TYPE OF CHALLENGE: Automated Scoring of Open Ended Reading Test Items

**SUBMISSION START: 9/16/2021 8:00 AM ET\
SUBMISSION END: 11/28/2021 5:00 PM ET**

Request for Information Webinar was held 10/4/2021 @ 12:00 ET.  The [slides are posted here](https://github.com/NAEP-AS-Challenge/info/blob/c782c585636cdb32bf7373291e93c7f34256ebba/2021_10_4_IES_AS_Challenge_RFI_Presentation.pdf). 

## Description

Automated Scoring using natural language processing is a well-developed
application of artificial intelligence in education. Results are
consistently demonstrated to be on-par with the inter-rater reliability
of human scorers for well-developed items (Shermis, 2014). Currently,
the National Assessment of Educational Progress (NAEP) makes extensive
use of constructed response items. Annually, contractors assemble teams
of human scorers who score millions of student responses to NAEP's
assessments. Previous internal research on the application of automated
scoring to NAEP items indicates that NAEP's items can be scored
successfully with automated scoring, using natural langage processing. Prior special studies have found that automated
scoring can perform as well as human raters in assigning scores, and
assigning a confidence level associated with the predicted score. Compared to human raters, no
evidence of biased student scoring based on demographic characteristics
was observed.

This challenge seeks to expand on this earlier work to ascertain whether
a wider array of automated scoring models can perform well with a
representative subset of NAEP Reading, constructed response items
administered in 2017 to students in grades 4 and 8. The ultimate goal is
to produce reliable and valid score assignments, provide additional
information about responses (e.g. length, cohesion, linguistic
complexity), and generate scores more quickly while saving money on
scoring costs.

There are two components to this challenge; entrants may submit
responses to one or both of these components:

1)  Component A - Item-Specific Models: Successful respondents will
    build a predictive model for each item that can be scored, using
    current state-of-the-art practices in operational automated scoring
    deployments. Extensive training data from prior human scoring administrations will be provided.
    The first-place prize for this challenge is \$15,000,
    with up to 4 runner-up prizes of \$1,250 each.

2)  Component B - Generic Models: Successful respondents will build a generic scoring model that will score items that
    were not included in the training dataset, but are from the same
    administration, subject, and grade level. The prize for this
    challenge is \$5,000, with up to 4 runner-up prizes of \$1,250 each.

Participants will be provided access to digital files that contain
information related the results of human-scored constructed responses to
reading assessment items that were administered in 2017, such as item
text, passage, scoring rubric, student responses, and human assigned
scores (both single and double scored). The responses correspond to
items that accompany two genres of 4^th^ and 8^th^ grade reading passages, literary and informational. Items for this challenge
are of two writing formats, short and extended constructed response.

The data set includes 20 items for the item-specific models, and 2 items
for the generic models. There are an average of 1,181 double-scored
responses per dataset, which are divided into a training dataset (50%),
a validation dataset (10%), and a test dataset (40%). The validation
dataset is augmented with a much larger number of single-scored
responses (average 23,000 per item). Detailed information about each
item is provided under "Item Information" below.

In addition to model accuracy compared to human scorers, successful
respondents to this Challenge will provide documentation of model
interpretability through a technical report that will be evaluated for
transparency, explanability, and fairness as further explained in
"Evaluation Criteria". The Federal Government is particularly interested
in submissions that provide accurate results and meet these objectives,
as they have been absent from a good deal of recent research in
automated scoring, particularly for solutions using artificial
intelligence (e.g. neural networks, transformer networks) and other
complex algorithmic approaches (Kumar & Boulanger, 2020). Both this documentation and predicted scores will be submitted simultaneously. The documentation
documentation will be evaluated before respondents' scored submissions are evaluated. Only
documentation that meets acceptance criteria (as specified below) will be
considered as valid submissions and evaluated for accuracy of the predicted
scores compared to the hold-out test dataset. 

This process is consistent
with the operational processes that the Department intends to use as
part of the approval process for scoring and reporting; only models that
can provide substantive validity evidence would be approved for
production use. This aspect of the Challenge is of critical importance
in educational contexts.

## 

## Eligibility Information

Institutions and individuals that have the ability and capacity to conduct research are
eligible to apply. Eligible applicants include, but are not limited to,
non-profit and for-profit organizations and public and private agencies
and institutions, such as colleges and universities.

## Requirements for Participation & Confidential Data Security 

-   The datasets used for this challenge contain student responses from previous NAEP assessments and are therefore considered NCES confidential materials. All participants must confirm that they are able to meet NCES Confidential Data security requirements. These requirements include restrictions on the use of data, security of data, and destruction of data when the analysis is completed. These requirements are specified in the security application documentation (available in this repository as ["application_documents.zip"](application_documents.zip). Security documentation must be completed and submitted before an applicant will be provided access to the response data. Data must also be destroyed/deleted within 30 days of completing the Challenge and all participants must submit a signed and witnessed form confirming that action. This form is also included within the security application.

-   It is possible, although unlikely, that responses may contain
    information about individual respondents. Individually identifiable
    information about students, their families, and their schools. Patricipants must agree that this will not 
    be revealed.

-   No person may:

    -   use any information for any purpose other than for the purposes
        of this activity

    -   make any publication whereby the data furnished by any
        particular person can be identified

-   The Education Sciences Reform Act of 2002 requires IES to develop
    and enforce standards to protect the confidentiality of students,
    their families, and their schools in the collection, reporting, and
    publication of data. The IES confidentiality statute is found in
    Public Law 107-279, section 183 (or as codified in 20 U.S.C. 9573).

-   Anyone who violates the confidentiality provisions of this Act when
    using the data shall be found guilty of a class E felony and can be
    imprisoned up to five years, and/or fined up to \$250,000.

No future NAEP contract work is guaranteed on the basis of performance
in this competition. Contracts are let on separate RFPs where performance
may be one of many criteria that may be used for evaluation.

## 

## Challenge Timeline 

|** |**Item**|**Duration (D)**|**Start**|**Finish**|
| :-: | :- | :-: | :-: | :-: |
|2.1|Challenge posting period|30|16-Sep|20-Oct|
|2.2|Request for information webinar||4-Oct|4-Oct|
|**2.3**|**Application deadline \***|||**20-Oct**|
|2.4|Provide dataset|| |28-Oct|
|2.5|Competitors prepare responses\*|30|29-Oct|28-Nov|
|**2.6**|**Response deadline**|||**28 Nov**|
|2.7|Select winner|||16-Dec|

\*Note: applications will be taken on a rolling basis and dataset access
will be provided as soon as possible (typically 48 hours after receipt of required documentation).

## Request for Information Webinar


A Request for Information Webinar was held 10/4/2021 @ 12:00 ET.  The [slides are posted here](https://github.com/NAEP-AS-Challenge/info/blob/c782c585636cdb32bf7373291e93c7f34256ebba/2021_10_4_IES_AS_Challenge_RFI_Presentation.pdf). 
Questions may also be sent via Github "issues" or via email to
<automated-scoring-challenge@ed.gov>.

## Frequently Asked Questions

*About the National Center for Education Statistics (NCES)*

The National Center for Education Statistics (NCES), one of the
principal federal statistical agencies, is the primary federal entity
for collecting and analyzing data related to education in the United
States and other nations. It provides statistical services for educators
and education officials at the federal, State, and local levels;
Congress; researchers; students; parents; the media and the general
public. NCES is located within the Institute of Education Sciences
(IES), the research arm of the U.S. Department of Education.

The National Assessment of Educational Progress (NAEP) is a
congressionally mandated project administered by NCES. NAEP is given to
a representative sample of students across the country. Results are
reported for groups of students with similar characteristics (e.g.,
gender, race and ethnicity, school location), and are not reported for individual students.
National results are available for all subjects assessed by NAEP. State
and selected urban district results are available for mathematics,
reading, and (in some assessment years) science and writing.

In 2009 NAEP began its transition to computer-based administration with
the hope of creating innovative performance assessments that more
closely reflected ways students were working and learning in classrooms,
increasing test security, enhancing cost effectiveness, reporting with a
faster turn-around time, and collecting performance/process data
with the goal of more comprehensively studying assessment results. The
potential of automated scoring is consonant with these goals, as long as
the procedure produces test scores with reliability and validity
indices that are comparable to current levels for the program. This challenge will help NAEP explore whether moving in this
direction is appropriate at this time.

## The Challenge

Participants may submit a response to either or both of the components
below.

## Component A: Item-Specific Models

For **item-specific models**, the participant shall create a model for each of twenty items.  
Respondents will be provided with training data from prior human scoring which will include the item text,
passage, scoring rubric, student responses, and human assigned scores
(both single and double scored). Respondents will use this information, and may supplement this information with external training data, features, or models 
to create a predictive model of human scores that is applied to a set of
"test" responses for which scores are not provided. The predicted scores
will be submitted as part of participants' responses.

## Component B: Generic Models

For **generic models**, the participant shall create a model for two
items similar in genre and format to those in Component A, but for which
only responses and scores will be provided. The model may be trained on
any or all items from Component A and may be supplemented with external
training data, features, or models. Respondents will use this
information to create a predictive model of human scores that is applied
to a set of "test" responses for which scores are not provided. The
predicted scores will be submitted as part of the participants' responses.

For both components, if your scoring engine links to an external routine or program that maps
semantic space or determines other linguistic features, you are
permitted to use these aids to make your predictions. However, you are
responsible for obtaining any licenses or permissions to do so. If your
scoring engine has these capabilities built in, those capabilities
should be documented in the technical report.

## Training Datasets

|**Component**|**Items Included** |
| :- | :- |
|Component A: Item-Specific Models|<p>- training data set (used for model building)</p><p>- cross-validation set (used for internal model evaluation)</p><p>- test data set (used for making score predictions) </p><p></p><p>The training and cross-validation sets have responses scored by two raters. The cross-validation set may be supplemented with single scored responses. The test data set will have text only, no scores. In addition to response and score data, item text, passage, scoring rubric, and additional relevant information will be provided. </p>|
|Component B: Generic Models|<p>- all items from Component A for different items (similar in genre and grade)</p><p>- test data set for new items (used for making score predictions) </p><p>- optional: additional training data, features or models</p>|

## Detailed Item Information

**Item-Specific Model Datasets**
|Item ID|Gr. | For.|Avg. No. Words|Total N|Miss.|DS Training N|DS Validation N|DS + SS Validation N|DS Test N|
| :- | :- | :- | :- | :- | :- | :- | :- | :- | :- |
|2017\_DBA\_DR08\_1715RE2T13\_05|8|SCR|28.11|21166|100|533|107|20207|426|
|2017\_DBA\_DR08\_1715RE2T13\_07|8|ECR|47.14|19934|385|495|99|19043|396|
|2017\_DBA\_DR08\_1715RE2T13\_08|8|SCR|28.28|19669|224|502|101|18989|402|
|2017\_DBA\_DR08\_1715RE4T05G08\_03|8|SCR|34.59|21197|81|539|108|20307|432|
|2017\_DBA\_DR08\_1715RE4T05G08\_06|8|ECR|51.29|21170|83|531|106|20214|425|
|2017\_DBA\_DR08\_1715RE4T05G08\_07|8|SCR|28.80|21088|62|529|106|20135|424|
|2017\_DBA\_DR08\_1715RE4T05G08\_09|8|ECR|34.87|20869|93|527|105|19920|422|
|2017\_DBA\_DR08\_1715RE4T08G08\_03|8|SCR|44.20|21380|92|543|109|20403|434|
|2017\_DBA\_DR08\_1715RE4T08G08\_06|8|SCR|32.82|21309|107|538|108|20340|431|
|2017\_DBA\_DR08\_1715RE4T08G08\_07|8|ECR|44.74|20990|185|529|106|20038|423|
|2017\_DBA\_DR08\_1715RE4T08G08\_09|8|SCR|32.95|20589|190|513|103|19665|411|
|2017\_DBA\_DR04\_1715RE1T10\_05|4|SCR|18.52|27806|355|690|138|26564|552|
|2017\_DBA\_DR04\_1715RE4T05G04\_03|4|SCR|18.63|28264|323|715|143|26977|572|
|2017\_DBA\_DR04\_1715RE4T05G04\_06|4|ECR|24.63|27462|327|682|137|26234|546|
|2017\_DBA\_DR04\_1715RE4T05G04\_07|4|SCR|14.55|26588|222|666|133|25389|533|
|2017\_DBA\_DR04\_1715RE4T05G04\_09|4|ECR|16.67|25651|426|634|127|24509|508|
|2017\_DBA\_DR04\_1715RE4T08G04\_03|4|SCR|23.90|28307|292|707|141|27034|566|
|2017\_DBA\_DR04\_1715RE4T08G04\_06|4|SCR|18.53|27533|329|694|139|26283|556|
|2017\_DBA\_DR04\_1715RE4T08G04\_07|4|ECR|20.55|25960|667|641|128|24806|513|
|2017\_DBA\_DR04\_1715RE4T08G04\_09|4|SCR|14.56|23720|597|583|117|22670|467|

**Generic Model Datasets**
|Item ID|Gr. | For.|DS Test N|
| :- | :- | :- | :- |
|2017\_DBA\_DR08\_1715RE2T13\_06|8|SCR|420|
|2017\_DBA\_DR04\_1715RE1T10\_07|4|ECR|539|

Item ID = Item identifier;
Gr. = Grade; 
For. = Format; 
SCR = Short Constructed Response;
ECR = Extended Constructed Response;						
Avg. No. Words = Average Number of Words;	
Miss. = Missing Data;
DS Training N = Double-Scored Training N;
DS Validation N = Double-Scored Validation N;
DS Test N = Double-Scored Test N;
DS+SS Validation N = Double-Scored + Single Scored Validation N

## Evaluation Criteria 

**Part 1: Model Interpretability**. Submissions must provide a
technical report that explains the model development process and results
appropriate to a technical audience with educational measurement
expertise. It is not expected that competitors will reveal confidential
information, but will provide evidence that enables an external reviewer
to assess the validity and fairness of the automated scoring process and
models. These reports will be submitted with submissions of predicted
scores, but must be approved as providing a sufficient degree of
interpretability per the criteria below before the response predictions
will be evaluated.

**Part 2: Model Accuracy**. Scoring performance will be evaluated
on the average quadratic weighted kappa (rounded to the third
decimal place) across all items in the competition. Competitors must score at least 99.5% of all scorable
responses (for which there is a human rating). During model construction, competitors will have access
to online resources to request further information or to make
suggestions about how to improve performance. See Appendix A for more
information on quadratic weighted kappa and how the winner of the
competition will be determined.

Model interpretability will be evaluated according to three criteria,
which will be equally weighted in the review:

a)  **Transparency** -- explanation of the ***process for model
    training and testing***, the features extracted from the text, and
    the algorithms used in model building. While these may describe a
    general workflow, they should also include the specific text
    features and algorithmic choices used to create the final models
    that score items in this Challenge.

b)  **Explainability** -- explanation of the ***resulting item model
    and/or individual scores*** that includes the input features
    considered, the modeling results, and algorithm choices.

c)  **Fairness** -- analysis into any **differences based on student
    demographic background** in automated scoring compared to those
    found in human-scored results.

Although not an evaluated criteria for winning the competition,
technical reports should include estimates for minimal training sample
sizes that would place the scoring engine's estimates within two percent
of the final predicted values.

|**Criteria**|**Responsive submissions will adequately address:**|
| :- | :- |
|<p></p><p>1.	Transparency</p>|<p>- Explain the model building process</p><p>- Include descriptions of features used for model building </p><p>- Include description of algorithm used for model building</p>|
|<p></p><p>2. Explainability</p>|<p>- Provide feature values and model statistics as appropriate to methods used </p><p>- Provide results from model training and cross validation</p><p>- Provide validity explanations that consider items and scoring rubrics</p>|
|<p></p><p>3. Fairness </p>|- Conducts analysis to ensure that models perform the same for different sub-populations, especially those from historically underserved communities. |

## Key Parameters

In conducting the work for the Challenge, there are several parameters
to consider:

-   Both team and individual competitors are eligible to participate.

-   Data sets will be provided in csv format.

-   All items in the training and test sets have been deemed “scorable” by human raters. There are responses in the validation set that were evaluated as “unscorable” and have no rating associated with them. They should be treated as missing data.


-   Teams must complete the required security documentation before
    datasets will be released. This documentation is avialable at: ["application_documents.zip"](application_documents.zip).

## Deliverables

Valid submissions will include reports with the following items:

-   A technical report that provides model interpretability as
    previously described.

-   Predicted scores (CSV format) from the test data responses.

-   A pricing sheet that includes all costs related to the production
    implementation of automated scoring: model training, item scoring,
    and any other infrastructure or organizational costs that would be
    required to integrate machine scoring into a live scoring system.
    While some costs (e.g. project management) may be variable, we
    expect fixed costs for well-known items such as model training, item
    scoring, system administration, and others.

## Challenge Administration Platform 

Most aspects of the Challenge will be administered via Github
(https://github.com/NAEP-AS-Challenge/info).

Specifically, this platform will be used for the following purposes:

1)  Information -- information about the challenge will be posted under
    "info" and available to the public.

2)  Questions -- all questions about the Challenge, datasets, or items
    should be posted as an "issue" and will be publicly available. Responses will typically be made within 24 business hours.

3)  Submissions -- to the Challenge should be submitted as a "pull
    request" under "https://github.com/NAEP-AS-Challenge/challenge_submissions" and will be private.

Please note that response data will be provided outside of Github to the
contact specified on the application.

## Prizes

The Department of Education is offering up to 10 prizes for a total
potential award of up to \$30,000 (\$20,000 for item-specific models,
\$10,000 for a generic model). The first-place prize for the item-specific
challenge is \$15,000, and the first-place prize for the generic model
is \$5,000. Up to 4 runner-up prizes in each category may be awarded
with cash prizes of \$1,250 each.

The winning results of the competition will be published in a technical
report summarizing the results of the competition. At the Department's
discretion, to assist with selecting winners, one or more of the most
highly rated challenge participants may be invited to present a virtual
presentation that reflects the basic elements of their technical report.

Any potential prizes awarded under this Challenge will be paid by
electronic funds transfer. Winners will be required to complete and
return an Automated Clearing House (ACH) Vendor/Miscellaneous Payment
Enrollment Form to ED within a given timeframe. The form collects
banking information needed to make an electronic payment (direct
deposit) to the winner. Award recipients will be responsible for any
applicable local, state, and federal taxes and reporting that may be
required under applicable tax laws.

## Rules

## Terms and Conditions

All entry information submitted
to [automated-scoring-challenge@ed.gov](mailto:automated-scoring-challenge@ed.gov) and
all materials, including any copy of the submission, become property of
the Department and will not be returned (See "Ownership and Licensing"
for information about use of these items). Furthermore, the Department
shall have no liability for any submission that is lost, intercepted, or
not received by the Department. The Department assumes no liability or
responsibility for any error, omission, interruption, deletion, theft,
destruction, unauthorized access to, or alteration of, submissions.

## Representations and Warranties/Indemnification

By participating in the Challenge, each entrant represents, warrants,
and covenants as follows:

1.  The entrants are the sole authors, creators, and owners of the
    submission;

2.  The entrant's submission:

    a.  Is not the subject of any actual or threatened litigation or
        claim;

    b.  Does not, and will not, violate or infringe upon the privacy
        rights, publicity rights, or other legal rights of any third
        party; and

    c.  Does not contain any harmful computer code (sometimes referred
        to as "malware," "viruses," or "worms").

3.  The submission, and entrants' implementation of the submission, does
    not, and will not, violate any applicable laws or regulations of the
    United States.

4.  Entrants will indemnify, defend, and hold harmless the Department
    from and against all third party claims, actions, or proceedings of
    any kind and from any and all damages, liabilities, costs, and
    expenses relating to, or arising from, entrant's submission or any
    breach or alleged breach of any of the representations, warranties,
    and covenants of entrant hereunder.

5.  The Department reserves the right to disqualify any submission that
    the Department, in its discretion, deems to violate these Official
    Rules, Terms, and Conditions in this notice.

## Ownership and Licensing

Each entrant retains full ownership of the algorithmic approaches to
their submission, including all intellectual property rights therein. By
participating in the Challenge, each entrant hereby grants to the
Department a royalty-free, nonexclusive, irrevocable, and worldwide
license to reproduce, publish, produce derivative works, distribute
copies to the public, perform publicly and display publicly, and/or
otherwise use the technical report and assessment of submitted scores
from each participant in the competition.

## Publicity Release

By participating in the Challenge, each entrant hereby irrevocably
grants to the Department the right to use the entrant's name, likeness,
image, and biographical information in any and all media for advertising
and promotional purposes relating to the Challenge.

## Disqualification

The Department reserves the right, in its sole discretion, to disqualify
any entrant who is found to be tampering with the entry process or the
operation of the Challenge, Challenge webpage, or other
Challenge-related webpages; to be acting in violation of these Official
Rules, Terms, and Conditions; to be acting in an unsportsmanlike or
disruptive manner, or with the intent to disrupt or undermine the
legitimate operation of the Challenge; or to annoy, abuse, threaten, or
harass any other person; and, the Department reserves the right to seek
damages and other remedies from any such person to the fullest extent
permitted by law.

## Disclaimer

The Challenge webpage contains information and resources from public and
private organizations that may be useful to the reader. Inclusion of
this information does not constitute an endorsement by the Department of
any products or services offered or views expressed.

The Challenge webpage also contains hyperlinks and URLs created and
maintained by outside organizations, which are provided for the reader's
convenience. The Department is not responsible for the accuracy of the
information contained therein.

## Notice to Challenge Entrants and Award Recipients

Attempts to notify entrants and award recipients will be made using the
email address associated with the entrants' submissions. The Department
is not responsible for email or other communication problems of any
kind.

If, despite reasonable efforts, an entrant does not respond within three
days of the first notification attempt regarding selection as an award
recipient (or a shorter time as exigencies may require) or if the
notification is returned as undeliverable to such entrant, that entrant
may forfeit the entrant's award and associated prizes, and an alternate
award recipient may be selected.

If any potential award recipient is found to be ineligible, has not
complied with these Official Rules, Terms, and Conditions, or declines
the applicable prize for any reason prior to award, such potential award
recipient will be disqualified. An alternate award recipient may be
selected, or the applicable award may go unawarded.

## Dates/Deadlines

The Department reserves the right to modify any dates or deadlines set
forth in these Official Rules, Terms, and Conditions or otherwise
governing the Challenge.

## Challenge Termination

The Department reserves the right to suspend, postpone, cease,
terminate, or otherwise modify this Challenge, or any entrant's
participation in the Challenge, at any time at the Department's
discretion.

## General Liability Release

By participating in the Challenge, each entrant hereby agrees that ---
(a) The Department shall not be responsible or liable for any losses,
damages, or injuries of any kind (including death) resulting from
participation in the Challenge or any Challenge-related activity, or
from entrants' acceptance, receipt, possession, use, or misuse of any
prize; and (b) The entrant will indemnify, defend, and hold harmless the
Department from and against all third party claims, actions, or
proceedings of any kind and from any and all damages, liabilities,
costs, and expenses relating to, or arising from, the entrant's
participation in the Challenge.

Without limiting the generality of the foregoing, the Department is not
responsible for incomplete, illegible, misdirected, misprinted, late,
lost, postage-due, damaged, or stolen entries or prize notifications; or
for lost, interrupted, inaccessible, or unavailable networks, servers,
satellites, Internet Service Providers, webpages, or other connections;
or for miscommunications, failed, jumbled, scrambled, delayed, or
misdirected computer, telephone, cable transmissions or other
communications; or for any technical malfunctions, failures,
difficulties, or other errors of any kind or nature; or for the
incorrect or inaccurate capture of information, or the failure to
capture any information.

These Official Rules, Terms, and Conditions cannot be modified except by
the Department in its sole and absolute discretion. The invalidity or
unenforceability of any provision of these Official Rules, Terms, and
Conditions shall not affect the validity or enforceability of any other
provision. In the event that any provision is determined to be invalid
or otherwise unenforceable or illegal, these Official Rules, Terms, and
Conditions shall otherwise remain in effect and shall be construed in
accordance with their terms as if the invalid or illegal provision were
not contained herein.

## Exercise

The failure of the Department to exercise or enforce any right or
provision of these Official Rules, Terms, and Conditions shall not
constitute a waiver of such right or provision.

## Governing Law

All issues and questions concerning the construction, validity,
interpretation, and enforceability of these Official Rules, Terms, and
Conditions shall be governed by and construed in accordance with U.S.
Federal law as applied in the Federal courts of the District of Columbia
if a complaint is filed by any party against the Department.

## Privacy Policy

By participating in the Challenge, each entrant hereby agrees that
occasionally, the Department may also use the entrant's information to
contact the entrant about Federal Challenge and innovation related
activities.

Please contact [automated-scoring-challenge@ed.gov](mailto:automated-scoring-challenge@ed.gov) should
you have any comments or questions about these Official Rules, Terms,
and Conditions.

## Other Information

*Accessible Format:* Individuals with disabilities can obtain this
document and a copy of the submission package in an accessible format
(e.g., braille, large print, audiotape, or compact disc) on request
to [automated-scoring-challenge@ed.gov](mailto:automated-scoring-challenge@ed.gov).

## Review

ED will screen all completed submissions to determine compliance with
submission criteria and determine eligible winner(s) following the
process described in Appendix A. 

## How To Enter

1.  Entrants must submit an application to participate by first completing the required security authorization forms to access NCES Confidential materials. These are provided at: https://github.com/NAEP-AS-Challenge/info/application-documents.zip.  Completed applications should be sent via email to: 
    [automated-scoring-challenge@ed.gov](mailto:automated-scoring-challenge@ed.gov) by the 10/20/2021 @ 5PM ET deadline. NOTE: Applications will be reviewed on a rolling basis starting 9/21/2021.

2.  Once approved, participants will be provided with secure access to
    the dataset and materials for the challenge.

3.  Submissions must be submitted as a Github pull request to:
    https://github.com/NAEP-AS-Challenge/challenge_submissions/. All submissions
    will be kept confidential. Submissions sould contain both the
    technical report and predicted scores. Submissions must be submitted
    by 11/28/2021 at 5:00 ET.
    
4. Within 30 days of final submissions, ALL participants are required to submit the signed and witnessed form confirming their destruction / deletion of all data that was provided for their use in this challenge.  This form is available, with instructions for submission, at: https://github.com/NAEP-AS-Challenge/info/application-documents.zip.

All entrants consent to the Official Rules,
Terms, and Conditions upon submitting an entry. Once submitted, a
submission may not be altered. The Department reserves the right to
disqualify any submission that the Department deems inappropriate. The
Department encourages entrants to submit entries, in the form of a
final, technical report, that contains both a narrative and predicted
scores as far in advance of the deadline as possible.

Individuals with disabilities who need an accommodation or auxiliary aid
in connection with the submission process should
contact [automated-scoring-challenge@ed.gov](mailto:automated-scoring-challenge@ed.gov).
If the Department provides an accommodation or auxiliary aid to an
individual with a disability in connection with the submission process,
the entry remains subject to all other requirements and limitations in
this notice.

## 

## Timeline and Notification

All submissions will be acknowledged as they are received. The winning
proposal(s) will be notified via email by 12/16/2021 at 5:00 ET.

## Appendix A ## 

Determining the Winner (Item-specific and Generic Prompt Competition)

The review process will consist of the following steps:

1)  Submissions will be reviewed to ensure that they are complete,
    including:
A)  The technical report for all entrants will be reviewed by a
    committee of panelists assembled by NCES at their discretion. If the
    panel determines that a statement meets the criteria of
    transparency, explainability, and fairness as explained previously
    in the Challenge document, the submission will be evaluated. If it
    does not meet these criteria, NCES will provide feedback to the
    participant and provide up to 14 calendar days for a new submission
    of the report, which will be reviewed again. If the submission meets
    the standard, the response will be reviewed further. If it does not,
    the response will be rejected. The rubric to be used in evaluating
    reports for interpretability is provided below.

B)  The number of items and responses scored will be counted.
    Competitors must score all items and 99.5% of the responses which
    have a legitimate human score. Entries will be rejected that do not
    provide sufficient scores to meet these criteria.

C)  The pricing sheet will be reviewed to ensure that it includes both
    fixed and variable costs for an operational deployment of the
    scoring model.

|**Criteria**|**Responsive submissions will adequately:**|
| :- | :- |
|<p></p><p>1.	Transparency</p>|<p>- Explain the model building process</p><p>- Include descriptions of features used for model building </p><p>- Include description of algorithm used for model building</p>|
|<p></p><p>2. Explainability</p>|<p>- Provide feature values and model statistics as appropriate to methods used </p><p>- Provide results from model training and cross validation</p><p>- Provide validity explanations that consider items and scoring rubrics</p>|
|<p></p><p>3. Fairness </p>|- Conduct analysis to ensure that models perform the same for different sub-populations, especially those from historically underserved communities. |


2)  All items will be scored using quadratic weighted kappa, a metric
    which measures the agreement between two ratings. The winner will be
    determined by the highest average quadratic weighted kappa across
    the items used in the competition, rounded to the third decimal
    place (for more information about quadratic weighted kappa, see
    information below). For the purposes of the competition, each item
    is weighted equally. This analysis will be performed separately for
    the Item-specific models and for the Generic model.

    a.  Results shall be numerically ranked from most accurate to least
        accurate, and the top responses will be chosen for prize awards and
        public recognition.

## Quadratic weighted kappa

Quadratic weighted kappa has been used to determine the winning
predictions in a number of high-stakes competitions where the goal is to
match human ratings (Shermis & Hamner, 2012; 2013; Shermis, 2014; 2015).

Quadratic weighted kappa allows disagreements to be weighted
differently and is especially useful when codes or ratings are
ordered. Three matrices are involved, the matrix of observed scores, the
matrix of expected scores based on chance agreement, and the weight
matrix. Weight matrix cells located on the diagonal (upper-left to
bottom-right) represent agreement and thus contain zeros. Off-diagonal
cells contain weights indicating the seriousness of that disagreement.
Often, cells one off the diagonal are weighted 1, those two off 2, etc.

Quadratic weighted kappa typically varies from 0 (random agreement
between raters) to 1 (complete agreement between raters). In the event
that there is less agreement between the raters than expected by chance,
the metric may go below 0. The quadratic weighted kappa is calculated
between the scores which are expected/known and the predicted scores.

Further information about Quadratic Weighted Kappa is available at: <https://en.wikipedia.org/wiki/Cohen%27s_kappa>. 

Items in the Challenge data sets have scores which can range from 0-2 to 0-4.
Any assigned score outside the range of the item is considered an
unscorable response (e.g., condition codes assigned by human raters), is
treated as missing data, and no prediction should be made for that
response. The quadratic weighted kappa is calculated as follows. First,
an N x N histogram matrix *x* is constructed, such that *x~ij~*
corresponds to the number of cases that have a rating of *i* (actual)
and received a predicted rating *j*. An N x N matrix of weights, *w*, is
calculated based on the difference between actual and predicted rating
scores.

An N x N histogram matrix of expected ratings, m, is calculated,
assuming that there is no correlation between rating scores. This is
calculated as the outer product between the actual rating\'s histogram
vector of ratings and the predicted rating\'s histogram vector of
ratings, normalized such that *m* and *x* have the same sum.

From these three matrices, the quadratic weighted kappa is calculated.

(see
<https://www.kaggle.com/aroraaman/quadratic-kappa-metric-explained-in-5-simple-steps>
for examples)

## Works Cited

Kumar, V., & Boulanger, D. (2020). Explainable Automated Essay Scoring:
Deep Learning Really Has Pedagogical Value. *Frontiers in Education*,
*5*, 572367. <https://doi.org/10.3389/feduc.2020.572367>

Shermis, M. D., & Hamner, B. (2012). *Contrasting state-of-the-art in
the machine scoring: Analysis*. National Council on Measurement in
Education, Vancouver, BC.

Shermis, M. D., & Hamner, B. (2013). Contrasting state-of-the-art
automated scoring of essays. In M. D. Shermis, J. C. Burstein (Eds.),
*Handbook of Automated Essay Evaluation: Current Applications and New
Directions* (pp. 298 - 312). Routledge.

Shermis, M. D. (2014). State-of-the-art automated essay scoring: A
United States demonstration and competition, results, and future
directions. *Assessing Writing*, *20*, 53--76.

Shermis, M. D. (2015). Contrasting state-of-the-art in the machine
scoring of short-form constructed responses. *Educational Assessment*,
*20*(1), 46 - 65.
https://doi.org/http://dx.doi.org/10.1080/10627197.2015.997617
