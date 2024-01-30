---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: about.avatar
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      text: 
    design:
      background:
        color: black
        text_color_light: true
        image:
          # Add your image background to `assets/media/`.
          filename: 10.25 x 13.25 F.JPG
          filters:
            brightness: 0.5
          size: cover
          position: center
          parallax: false
  - block: markdown
    content:
      title: ''
      subtitle: ''
      text: |-
        I am a Medical Informatics postdoctoral fellow at the Boston VA Healthcare system and a Catalyst fellow at MIT. My primary program of research takes a critical approach to improving the measurement, classification, and identification of digital phenotypes for adverse health outcomes across individual, interpersonal, and community levels. My secondary line of research is concentrated on the development of a clinical decision-making systems that capitalize on common factors across psychotherapeutic processes to aid in personalized psychotherapy treatment selection. 

        **Interest**: 
        - Risk Predicition
        - Digital Theraputics
        - Healthcare Innovation
        - Problem Areas: 
          - Opioid Crisis
          - Suicide
          - Pscyhosis
          - HIV
          - PTSD

    design:
      columns: '1'
  - block: collection
    content:
      title: Recent News
      subtitle: ''
      text: ''
      # Page type to display. E.g. post, talk, publication...
      page_type: publication
      # Choose how many pages you would like to display (0 = all pages)
      count: 5
      # Filter on criteria
      filters:
        author: ""
        category: ""
        tag: ""
        exclude_featured: false
        exclude_future: false
        exclude_past: false
        publication_type: ""
      # Choose how many pages you would like to offset by
      offset: 0
      # Page order: descending (desc) or ascending (asc) date.
      order: desc
    design:
      # Choose a layout view
      view: compact
      columns: '1'

- block: experience
    content:
      title: Clinical Experience
      # Date format for experience
      #   Refer to https://docs.hugoblox.com/customization/#date-format
      date_format: Jan 2006
      # Experiences.
      #   Add/remove as many `experience` items below as you like.
      #   Required fields are `title`, `company`, and `date_start`.
      #   Leave `date_end` empty if it's your current employer.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - title: Postdoctoral Psychologist
          company: Boston Veterans Affairs Healthcare System
          company_url: 'https://www.va.gov/boston-health-care/locations/brockton-va-medical-center/'
          company_logo: Veterans_Affairs_logo
          location: Boston, Massachusetts
          date_start: '2022-08-01'
          date_end: '2023-09-01'
          description: |2-
            * Provided clinical intake services for veterans with trauma and stress-related disorders seeking outpatient mental healthcare
            * Maintain a caseload of up to six individual psychotherapy cases, providing Cognitive Processing Therapy (CPT), Prolonged Exposure (PE), Cognitive Behavioral Therapy for Insomnia (CBT-I), and Written Exposure Therapy (WET)

        - title: Psychology Intern
          company: Beth Israel Deaconess Medical Center/Massachusetts Mental Health Center
          company_url: 'https://www.bidmc.org/medical-education/medical-education-by-department/psychiatry/clinical-psychology-internship-program'
          company_logo: BIDMC_HMS_Stacked
          location: Boston, Massachusetts
          date_start: '2021-07-01'
          date_end: '2022-06-31'
          description: |2-
            
            Rapid Access to Flexible Treatment (RAFT):
            * Providing clinical intake services for high-risk adults attending partial hospitalization day program for individual with psychotic-spectrum disorders and/or character pathologies
            * Maintain a caseload of up to four individual psychotherapy, providing Acceptance and Commitment Therapy (ACT), Dialectical Behavior Therapy (DBT), and CBT for patient presenting with personality and psychosis spectrum disorders
            * Co-leading three weekly anger management, CBT, and DBT oriented groups in an outpatient setting
            * Aid in treatment and discharge planning as well as systems meetings with multidisciplinary team
            * Aid in training and supervision of psychology externs and psychiatry residents
            Adult Outpatient Psychiatry Service:
            * Maintain a caseload of up to ten individual psychotherapy, providing Psychodynamic, Meta-cognition, Cognitive, and Behavioral based therapies for Department of Mental Health patients presenting with psychosis spectrum disorders
            * Co-lead one weekly long-term psychodynamic group for adults with schizophrenia 
            * Conduct focal psychiatric assessments, triage, and treatment planning for adult patients seeking treatment of psychosis spectrum disorders
        
        - title: Psychology Extern
          company: Jacobi Health + Hospitals
          company_url: 'https://www.nychealthandhospitals.org/locations/jacobi/'
          company_logo: NYC_Health_+_Hospitals_logo
          location: Bronx, New York
          date_start: '2020-09-01'
          date_end: '2021-06-31'
          description: |2-
            
            Psychiatric Inpatient Unit (8A):
            * Providing individual psychotherapy for adults admitted to mono- and bi-lingual psychiatric inpatient unit for psychotic disorders, major affective disorders, substance-abuse disorders, or a range of character pathologies
            * Conducting cognitive assessments and clinical intake for admission and psycho-diagnostic purposes
            * Co-leading two weekly insight-oriented and skills-based group on inpatient unit
            * Aid in treatment and discharge planning as well as, family and community meetings with multidisciplinary team
            * Participate in therapeutic milieu of unit and provide weekly updated on patient prognosis to multidisciplinary team
            Comprehensive Addiction Treatment Center Outpatient (CATC):
            * Maintain a caseload of up to three individual psychotherapy, providing Motivational Interviewing, and Behavioral approached for patients presenting with substance use disorders
            * Co-lead three weekly harm-reduction and DBT groups for adults seeking substance use treatment
            * Conduct focal psychiatric assessments, intakes, triage, and treatment planning for adult patients seeking substance use treatment
            Adult & Pediatric HIV Comprehensive Services:
            * Maintain a caseload of up to three individual psychotherapy patients living with HIV/AIDS, presenting mood and anxiety disorder
            * Co-lead weekly support group for adults living with HIV/AIDS
        
        - title: Student Psychologist
          company: Regulation of Emotion in Anxiety and Depression, Teachers College, Columbia University
          company_url: 'https://www.emotionregulationtherapy.com/'
          company_logo: ERT Logo.jpeg
          location: New York, New York
          date_start: '2020-04-01'
          date_end: '2020-09-01'
          description: |2-
            
            Emotion Regulation Therapy for the COVID-19 Pandemic:
            * Conducted twice a week, manualized eight session Emotion Regulation Therapy for adult outpatients experiencing distress related to COVID-19 pandemic via synchronous telehealth 
            * Clients have a diagnosis of mood and anxiety disorders and ranging in age from 23 to 53 years, with varying degrees of COVID-19 related distress from loss of loved ones to their own experiences of contracting COVID-19
        
        - title: Clinical Intake Extern
          company: Dean Hope Center for Educational and Psychological Services
          company_url: 'https://www.tc.columbia.edu/deanhope/'
          company_logo: DHCEPS logo.png
          location: New York, New York
          date_start: '2020-01-01'
          date_end: '2020-05-31'
          description: |2-
            
            * Provided weekly on-call coverage for assessment of suicide risk and appropriateness for treatment at training clinic
            * Bi-weekly supervision with clinic director and clinical social worker on prognosis and triage plan for new applicants

        - title: Psychology Extern
          company: VA New York Harbor Healthcare System
          company_url: 'https://www.va.gov/new-york-harbor-health-care/locations/manhattan-va-medical-center/'
          company_logo: Veterans_Affairs_logo
          location: New York, New York
          date_start: '2019-07-01'
          date_end: '2020-06-30'
          description: |2-
            
            Psychotherapy Research Development Program:
            * Provided individual psychotherapy for adult veterans with PTSD, severe mood and anxiety disorders, and character disorders, utilizing a variety of treatment approaches, including long-term psychodynamic psychotherapy, short-term Dynamic Interpersonal Therapy (DIT), Formulation-Based CBT, and CBT-I
            * Conducted cognitive and personality assessments for psycho-diagnostic purposes, writing integrative reports, and providing feedback to veterans
            * Conducted neuropsychological assessment of veterans with Traumatic-Brain Injuries, Alzheimer's disease, vascular dementia, Parkinson's disease, and strokes 
            * Co-led weekly Systems theory informed insight-oriented group on dual-diagnosis inpatient unit

        - title: Psychometrician
          company: Private Practice
          company_url: 'https://www.va.gov/new-york-harbor-health-care/locations/manhattan-va-medical-center/'
          company_logo: Psi
          location: New York, New York
          date_start: '2019-12-01'
          date_end: '2020-03-30'
          description: |2-
            
            * Conduct psychological and occupational assessment for adults seeking mental health services in a private practice setting
            * Administered tests assessing cognitive functioning, executive functioning, memory, & personality using standardized clinician-administered tools and projective tests

        - title: Supervisor Training Practicum
          company: Dean Hope Center for Educational and Psychological Services
          company_url: 'https://www.tc.columbia.edu/deanhope/'
          company_logo: DHCEPS logo.png
          location: New York, New York
          date_start: '2019-01-01'
          date_end: '2019-07-30'
          description: |2-
            
            * Provide weekly supervision to licensed counselor for weekly psychotherapy case
            * Weekly didactics on theories of supervision and process/peer supervision group

        - title: Psychology Extern
          company: New York-Presbyterian- Weill Cornell Medicine, Program for Anxiety and Traumatic Stress Studies
          company_url: 'https://www.va.gov/new-york-harbor-health-care/locations/manhattan-va-medical-center/'
          company_logo: WCM_NYP logo.png
          location: New York, New York
          date_start: '2018-07-01'
          date_end: '2019-06-30'
          description: |2-
            
            Military Family Wellness Clinic:
            * Provide weekly individual psychotherapy services, in Cognitive Behavioral Therapy for Insomnia, Interpersonal Psychotherapy, Cognitive Processing Therapy, and Prolonged Exposure, to veterans and veteran family members suffering from mood, anxiety and post-traumatic stress disorders
            * Maintained a caseload of up to three individual psychotherapy patients presenting with PTSD and co-occurring disorders
            * Conduct weekly unstructured intakes and standardized diagnostic assessments, using the Clinician-Administered PTSD Scale for DSM-5 (CAP-5) and Mini International Neuropsychiatric Interview (MINI), for adult clients seeking services at the clinic
            William Randolph Hearst Burn Center:
            * Provide consultation to assess psychiatric symptoms and brief cognitive-behavioral interventions at bedside to recently traumatized adult patients admitted to the medical inpatient unit
            * Receive live in-room supervision and consultation during bedside assessment and intervention
            * Provide manualized weekly individual Prolonged-Exposure therapy to victims of burn injuries in an outpatient setting as a part of RCT
            * Collaborate with multidisciplinary teams consisting of psychology, social work, surgery, physical therapists, and nursing staff to discuss new admissions, discharge planning, risk assessment, and overall clinical status of patients admitted to the inpatient burn unit

        - title: Student Psychologist
          company: Regulation of Emotion in Anxiety and Depression, Teachers College, Columbia University
          company_url: 'https://www.emotionregulationtherapy.com/'
          company_logo: ERT Logo.jpeg
          location: New York, New York
          date_start: '2018-09-01'
          date_end: '2019-09-01'
          description: |2-
            
            Emotion Regulation Therapy for the COVID-19 Pandemic:
            * Conduct weekly manualized 8 or 16 session Emotion Regulation Therapy for adult outpatients as part of a clinical trial
            * Clients have a diagnosis of mood and anxiety disorders and ranging in age from 25 to 29 years 

        - title: Student Psychologist
          company: Dean Hope Center for Educational and Psychological Services
          company_url: 'https://www.tc.columbia.edu/deanhope/'
          company_logo: DHCEPS logo.png
          location: New York, New York
          date_start: '2017-01-01'
          date_end: '2021-06-30'
          description: |2-
            
            Advanced Neuropsychological Assessment:
            * Conducted neuropsychological and psych-educational assessments for adults
            * Assisted in WADA assessments for young adults with epilepsy 
            * Administered tests assessing cognitive functioning, executive functioning, memory, & personality along with projective tests
            Psychodynamic Psychotherapy:
            * Conduct intakes and twice weekly psychodynamic psychotherapy sessions for adult outpatients presenting at a community mental health clinic
            * Clients ranging in age from 29 to 77 years 
            * Develop and implement treatment plans from varying approaches including relational, object-relations, transference-focused, and relational modalities
            Cognitive-Behavioral Therapy:
            * Conducted intakes and weekly Cognitive Behavioral psychotherapy sessions for adult outpatients presenting at a community mental health clinic
            * Clients ranged in age from 25 to 30
            * Implemented treatment approaches drawing from the Unified Protocol for Transdiagnostic Treatment of Emotional Disorders and third wave CBT approaches including Acceptance and Commitment Therapy and Mindfulness-Based Cognitive Therapy
            Psychological Assessment:
            * Conducted psychological and psych-educational assessments for adults and children
            * Administered tests assessing cognitive functioning, executive functioning, memory, & personality along with projective tests 

        - title: Peer counselor
          company: International House
          company_url: 'https://www.ihouse-nyc.org/'
          company_logo: ihouse_logo.png
          location: New York, New York
          date_start: '2015-06-01'
          date_end: '2026-05-30'
          description: |2-

          * Provide on-call service for crisis intervention, individual supportive counseling, psychotherapy, and legal & medical referrals
          * Conduct monthly supervision sessions with assigned Resident Fellows to provide support, identify and resolve issues regarding roommate conflicts and floor events 
          * Assisted in development and maintenance of mental health resource website for residents

    design:
      columns: '2'


---
