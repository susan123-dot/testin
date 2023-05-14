
# Software Testing
1. Fundamental of Testing
    - What is Testing?

        Testing is a process of evaluating a system or software to determine its functionality, performance, or other attributes, with the aim of identifying defects or validating its conformance to requirements. It involves executing various test cases, analyzing results, and ensuring that the system meets the desired quality standards before deployment.
    - Typical Objectives of Testing
        - Finding Errors and Bugs in System
        - Ensure that system will meet specific requirement or not
        - improve its quality, reliability, and user satisfaction
    - Testing & Debugging

        Testing is the process of verifying system or software will meet the specific requirement or not and debugging is the finding and fixing of errors and defects of the code.
    - Quality Assurance and Testing

        Quality assurance is broader set of activities about SDLC to get high quality product and Testing is finding and fixitng errors and defects in system to meet specified requirements.
    -  Errors, Defects, and Failures

        Errors are mistakes made during the development process, defects are the presence of faults in the software, and failures occur when the software does not perform as intended, often due to errors or defects.
    - Defects, Root Cause and Effect

        Defects are flaws or issues in a product, root causes are the underlying reasons for those defects, and effects are the impacts that result from the presence of defects.

    - Seven Testing Principles
        - Testing shows the presence of defects
        
            Testing helps to uncover defects and identify areas of weakness in the software.
        - Exhaustive testing is impossible
        
            It is impossible to test all possible combinations and scenarios, so testing efforts should be focused on high-risk areas.
        - Early testing
        
            Testing activities should start as early as possible in the software development life cycle to identify and address defects early on.
        - Defect clustering
            
            Typically, a small number of modules or components contain the majority of defects, so testing efforts should be concentrated on those areas.
        - Pesticide paradox
            
            Repeated testing with the same test cases can lead to diminishing returns, so test cases need to be regularly reviewed and updated.
        - Testing is context-dependent

            Testing strategies and techniques should be tailored to suit the specific context of the project, including its objectives, risks, and constraints.
        - Absence of errors fallacy
            
            The absence of detected defects does not guarantee the absence of defects, so testing cannot guarantee a defect-free software, but it can help mitigate risks and improve software quality.
    - Types of Testing
        - Unit Testing

            It invloves testing the individual components of the software.
        - Integration Testing

            This type of testing is used to check interaction between different components of the software.
        
        - System Testing

            It involves in testing the entire system to identify that all components are working together or not.
        - Acceptance Testing

            It is the process of determining that system meets user's requirement or not.  
        - Usability Testing

            It evaluates the software's user friendliness and how easy to use.
        - Recovery Testing

            It involves in testing the software ability to recover from crashes or failures.
        - Functional Testing

            This type of testing verifies that the software functions as intended and meets the specified functional requirements.
        - Performance Testing

            It involves testing the software's performance and responsiveness under different load conditions to assess its scalability, speed, and stability.
        - Security Testing

            It focuses on identifying vulnerabilities and weaknesses in the software to protect it from potential security threats.
        - Regression Testing

            It involves retesting the modified or added parts of the software to ensure that the changes have not introduced any new defects or issues.
        - Compatibility Testing

            This testing verifies that the software is compatible with different operating systems, browsers, devices, or other software configurations.
        - Explorotary Testing

            It is an ad hoc testing approach where testers explore the software without any specific test scripts, aiming to uncover defects and gain insights.
        - Load Testing

            It tests the software's performance under expected load conditions to assess its stability and response time.
        - Stress Testing

            This type of testing evaluates the software's behavior and performance under extreme conditions or beyond its normal operational capacity.
        - Localization Testing

            It checks if the software is properly adapted to meet the requirements of a specific locale or language.
    - Test Process
        - Test Design
            
            In this initial stage, the test objectives, scope, and strategy are defined. Test planning involves identifying the testing goals, establishing the test deliverables, determining the test environment and resources, and creating a test plan that outlines the testing activities and schedules.
        - Test Planning
            
            In this stage, test scenarios, test cases, and test data are developed based on the requirements and design specifications. Test design involves identifying the test conditions, creating test cases to validate each condition, and preparing the necessary test data to execute the tests.
        - Test Environment Setup
            
            The test environment includes the hardware, software, and network configurations required for testing. In this stage, the test environment is set up and configured to replicate the target production environment. This may involve installing necessary software, hardware, and network configurations to create a stable and representative testing environment.
        - Test Execution
            
            This stage involves running the test cases based on the test design and capturing the test results. Test execution may include manual or automated testing techniques, depending on the available resources and project requirements. Testers perform the tests, record any observed defects or issues, and document the test results for further analysis.
        - Test Reporting and Defect Tracking
            
            The test results and any discovered defects are documented and reported in this stage. Test reports summarize the executed tests, their outcomes, and any issues encountered. Defect tracking tools may be used to log, track, and manage the identified defects throughout the testing process.
        - Defect Analysis and Retesting
            
            After defects are reported, they are analyzed to understand their root causes and severity. The development team may fix the defects, and the testers will perform retesting to ensure that the issues have been resolved without introducing new problems.
        - Test Closure
            
            In the final stage, the test activities are concluded. This includes analyzing the test results and metrics, assessing the overall quality of the software, and preparing test closure reports. Test closure also involves documenting lessons learned during the testing process to improve future testing efforts.
    - The Pshychology of Testing
        - Attention to Details

            Effective testing requires attention to detail, as testers need to meticulously examine the software and its behavior. Attention to detail involves being thorough, observant, and focused on identifying potential defects and anomalies. Testers who possess strong attention to detail are more likely to spot critical issues and ensure a higher level of quality.
        - Curiosity

            Curiosity plays a significant role in testing. Testers with a curious mindset are motivated to explore and uncover potential issues, even beyond the specified requirements. They ask questions, dig deeper, and proactively seek out areas of the software that may be prone to defects. Curiosity-driven testing often leads to the discovery of valuable insights and improvements.
        - Critical Thinker

            Testing involves critical thinking skills, including analysis, problem-solving, and decision-making. Testers need to interpret requirements, design effective test cases, and assess the impact of defects. They must think critically to identify potential risks, anticipate user behavior, and prioritize testing efforts. Strong critical thinking skills contribute to more effective and efficient testing.
        - Skepticism

            A healthy dose of skepticism is essential in testing. Testers should approach the software with a questioning mindset, challenging assumptions and verifying expectations. Being skeptical helps testers avoid confirmation bias and thoroughly evaluate the software, increasing the chances of detecting defects that may otherwise be overlooked.
        - Problem Solving under Pressure

            Testing can be challenging, especially when faced with tight deadlines, complex scenarios, or critical issues. Testers must handle pressure and solve problems effectively. The ability to think clearly, remain composed, and make sound decisions even in high-pressure situations is crucial for maintaining quality throughout the testing process.
        - Collaboration and Communication
            
            Effective collaboration and communication are vital in testing, particularly when working with developers, stakeholders, and other team members. Testers need to clearly articulate their findings, report defects, and provide feedback. Good interpersonal skills and the ability to collaborate positively contribute to smoother testing processes and better outcomes.
        - Learning and Adaptibility

            The field of software testing is constantly evolving, with new tools, methodologies, and technologies emerging. Testers need to be adaptable, open to learning, and willing to embrace changes. The ability to quickly acquire new skills, stay updated with industry trends, and adapt to evolving testing practices is essential for staying effective and relevant in the field.
    - Static and Dynamic Testing
        - Static Testing: Static testing is a software testing approach that focuses on reviewing and analyzing the software's documentation, requirements, and code without executing the program.
        - Dynamic Testing: Dynamic testing is an essential software testing approach that involves executing the software and observing its behavior to ensure that it functions correctly.
    - Review Process
        The review process is a systematic approach to evaluating and providing feedback on various artifacts, documents, or components related to software development.
        - Planning 

            The review process begins with planning, where the objectives, scope, and schedule for the review are determined. The artifacts or components to be reviewed are identified, and the roles and responsibilities of the reviewers are defined.
        - Preparation

            Reviewers prepare themselves by familiarizing themselves with the artifacts or components under review. They study the relevant documentation, requirements, or specifications to gain a comprehensive understanding of the subject matter.
        - Conducting the Review

            The review session takes place, either in person or through a collaborative online platform. The reviewers systematically examine the artifact or component, looking for errors, inconsistencies, or areas that need improvement. They may use checklists, guidelines, or best practices to ensure a thorough review.
        - Communication Discussion

            During the review, reviewers communicate their findings and observations. They discuss any identified issues, ask questions, and seek clarification from the authors or stakeholders. The goal is to foster a constructive dialogue and gather multiple perspectives to enhance the review outcomes.
        - Issue Resolution

            Issues or defects discovered during the review are documented and assigned to the appropriate parties for resolution. Reviewers may provide recommendations or suggestions on how to address the identified problems. The authors or developers then work on rectifying the issues and making necessary improvements.
        - Follow-Up

            After the review, there may be a follow-up session to verify that the identified issues have been addressed satisfactorily. The progress of issue resolution is tracked, and any remaining concerns are discussed. The review process may also involve capturing lessons learned to improve future reviews and development practices.
    - Test Techniques
        - Black-Box Testing Techniques
        - White-Box Testing Techniques
        - Experienced-Based Techniques