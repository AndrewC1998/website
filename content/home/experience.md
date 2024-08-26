+++
# Experience widget.
widget = "experience"  # See https://sourcethemes.com/academic/docs/page-builder/
headless = true  # This file represents a page section.
active = true  # Activate this widget? true/false
weight = 50  # Order that this section will appear.

title = "Academic Experience"
subtitle = ""

# Date format for experience
#   Refer to https://sourcethemes.com/academic/docs/customization/#date-format
date_format = "Jan 2006"

# Experiences.
#   Add/remove as many `[[experience]]` blocks below as you like.
#   Required fields are `title`, `company`, and `date_start`.
#   Leave `date_end` empty if it's your current employer.
#   Begin/end multi-line descriptions with 3 quotes `"""`.

[[experience]]
  title = "Open Source Developer"
  company = "Google Summer of Code & R Project for Statistical Computing"
  company_url = "https://summerofcode.withgoogle.com/"
  location = "Lancaster"
  date_start = "2018-05-29"
  date_end = "2018-08-31"
  description = """Over the summer, I was working with [Professor David Matteson](https://stat.cornell.edu/people/faculty/david-s-matteson) at Cornell University and Senior Lecturer [Dr. Rebecca Killick](http://www.lancs.ac.uk/~killick/) at Lancaster University to implement a new R package: changepoint.online. Although this work officially ended in August, I have continued developing this project further and begun writing a paper documenting the findings from the summer. Further work, such as the development of online non-parametric changepoint detection is now in the process of being developed.

Throughout the summer I was using R, C++ and C to create the R package and was working from Lancaster University in an office with Ph.D. students. This opportunity meant I was working in an office where new Statistical research were being developed and this enabled me to learn about areas of Statistics that had not been covered by my degree’s curriculum.

A brief summary of the project is provided below:
There are many R packages available for offline changepoint detection but, to the knowledge of myself and the mentors, only one for online change point detection (cpm). This package would implement traditional "resetting" methodology, which means once a change has occurred previous data is forgotten. This project would bring the accuracy benefits of the offline methodology to the online setting, allowing users to implement the state of the art offline methods in a computationally efficient manner for online use."""

[[experience]]
  title = "Open Source Developer"
  company = "Google Summer of Code & R Project for Statistical Computing"
  company_url = "https://summerofcode.withgoogle.com/"
  location = "Lancaster"
  date_start = "2019-05-28"
  date_end = "2019-09-01"
  description = """ Detecting changes in statistical properties of a time series is important in a large number of fields. A large amount of research has taken place considering changes in mean and variance in time series. However, a typical assumption is that the error process is independent. Similarly more and more users of existing packages, for example changepoint, are facing problems using real world data due to the dependence structures present. There are several methods available in the literature that are not available in open source code. This project plans to address this by adding this functionality to a popular CRAN package, changepoint.

The project implements several changes in second order structure algorithms including the commonly used AR(p) structure and changes in variance and autocovariance (rather than spectra) through the LSW model.

The Locally Stationary Wavelet (LSW) process can capture many dependence structures. Of particular interest in changepoint applications is the fact that a piecewise second order time series will have its structure encoded as piecewise constant sequences in the local wavelet periodogram - a feature noted by Cho and Fryzlewicz (2012). Consequently when using the LSW framework for changepoint methods we do not need to be prescriptive about the structure of the dependence beyond the requirements of the LSW definition. A barrier to the current implementation in wbsts is that the majority of practitioners are familiar with variance and autocorrelation but not necessarily spectral decompositions - let alone time-varying spectra. For this reason we are seeking to implement a method to detect changes in variance and covariance through the non-parametric LSW model instead of a change in spectra."""

[[experience]]
title = "Team Leader"
company = "Enactus Lancaster"
company_url = "http://enactusuk.org"
location = "Lancaster"
date_start = "2018-03-15"
date_end = "2019-06-15"
description = """As the Team Leader of Enactus Lancaster I was ultimately responsible for all activities of the society. I lead the executive committee and was involved in the creating and overseeing of long term strategic plans. I regularly liaised with Enactus UK where I ensured that all necessary information is passed between Enactus UK and Enactus Lancaster. Furthermore, through leading over 80 students at Lancaster University across several projects, I ensure that all projects are kept to schedule and our beneficiaries are positively impacted through entrepreneurial action. Details of the projects can be found in the Enactus section."""

[[experience]]
title = "Radio Presenter"
company = "Bailrigg FM - The Atomic Fridge"
company_url = "https://bailriggfm.co.uk"
location = "Lancaster"
date_start = "2017-11-27"
date_end = "2019-01-01"
description = """I, along with two other students, hosted a weekly radio show, "The Atomic Fridge", which is broadcast on Thursday mornings and has featured in the Maths departmental newsletter. We interviewed guests about their fields of study. Several guests agreed to appear on the show including: [Professor Alexander Belton](https://www.lancaster.ac.uk/maths/people/alexander-belton), [Professor Roger Jones](https://www.lancaster.ac.uk/physics/about-us/people/roger-william-lewis-jones) and [Dr. Mark MacDonald](https://www.maths.lancs.ac.uk/~macdonam/). We discussed mathematics, physics and statistical research ideas with the intention of broadening listeners' knowledge of these areas. The radio show has allowed me to explore and understand areas of mathematics, statistics and physics that I would not normally have encountered as an undergraduate student."""

[[experience]]
title = "Mathematics Departmental Ambassador"
company = "Lancaster University Mathematics and Statistics Department"
company_url = "https://www.lancaster.ac.uk/maths/"
location = "Lancaster"
date_start = "2017-10-09"
date_end = "2019-06-26"
description = """Alongside my studies at Lancaster, I was also a Mathematics Ambassador. As a Mathematics ambassador it was my job to conduct campus tours, work on behalf of my department and represent the university on Open Days. For the Open Days, I showed potential and current applicants around the university accommodation and gave them any information that they required.
As a Mathematics ambassador, I also presented lectures and talked about student life at Lancaster, what it is like to study Maths and answered any subject specific questions the applicants had."""

[[experience]]
title = "Robotics Teacher"
company = "Tamwood International College LTD."
company_url = "https://www.tamwood.com/tamwood-camps/teen-robotics-camp/"
location = "Boston"
date_start = "2017-07-03"
date_end = "2017-08-24"
description = """Over the summer of 2017 I worked as a full time teacher and taught robotics to 13 to 17 year olds for Tamwood Camps. This meant writing and delivering lessons and evaluating students work. Furthermore, I also took the children on several excursions to MIT where more lessons took place.

During the lessons, the children learned how to build basic robots as well as gain a deeper understanding for programming. This was the first year the robotics programme was run and I was the sole teacher in the first year. The programme is now being run again this year."""

[[experience]]
title = "Lead Department Representative"
company = "Lancaster University Students Union"
company_url = "https://lancastersu.co.uk/reps"
location = "Lancaster"
date_start = "2017-07-03"
date_end = "2019-08-24"
description = """Having represented the Department for three years, it was my job to attend student-staff meetings and other events for the Mathematics and Statistics Department. The nature of this role meant I listened to the concerns raised by the students within my department; discussed these issues with staff; worked to find the best possible resolution for all parties; and fed back all of the relevant information to my fellow students.

In my third year, I took on the role as Lead Representative. Tasks for this role included creating agendas for all staff-student meetings, ensure that all students, including the other representatives, have their voices heard and chairing all meetings for the Mathematics and Statistics Department. This role meant I interacted with undergraduates and postgraduates."""

[[experience]]
title = "Private Tutor"
company = "Freelance"
company_url = ""
location = "London"
date_start = "2018-06-01"
date_end = ""
description = """During my undergraduate and postgraduate degrees, I worked as a freelance private tutor specialising in mathematics and physics. I tutored GCSE up to first year degree level. As someone who is passionate in following a career in academia and lecturing, I really engage with the opportunity to teach others especially those in need of mathematics tutoring at an undergraduate level.

Please contact me if you are interested in private lessons or have any other enquiries."""

[[experience]]
title = "Postgraduate Representative"
company = "Imperial College London Department of Mathematics"
company_url = "https://www.imperial.ac.uk/statistics"
location = "London"
date_start = "2019-09-01"
date_end = "2020-10-01"
description = """Alongside my studies at Imperial, I was also the MSc Statistics Representative. As an MSc rep, it was my job to plan events, engage the students and enable an open dialogue between the staff and the students. Due to the COVID-19 pandemic, i had to adapt my event plans and arranged for online coffee breaks, mathematics seminars and wellbeing events. """

[[experience]]
title = "Postgraduate Research Representative"
company = "Imperial College London Department of Mathematics"
company_url = "https://www.imperial.ac.uk/mathematics/postgraduate/doctoral-programme/current-students/key-contacts/"
location = "London"
date_start = "2020-09-01"
date_end = ""
description = """Alongside my research at Imperial, I am also the PhD Statistics Representative. As an PhD rep, it is my job to plan events, engage the students and enable an open dialogue between the staff and the students. """
+++
