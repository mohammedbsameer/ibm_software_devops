name: User Story
description: Template for writing well-structured Agile User Stories
title: "User Story: [Short Description]"
labels: ["user-story"]
assignees: []
body:
  - type: markdown
    attributes:
      value: |
        **As a** [role]  
        **I need** [function]  
        **So that** [benefit]  
          
        ### Details and Assumptions
        * [document what you know]
          
        ### Acceptance Criteria  
          
        ```gherkin
        Given [some context]
        When [certain action is taken]
        Then [the outcome of action is observed]
        ```
