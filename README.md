# ng-timeline

## Requirements

- Side menu on the left displaying all the rows
    - Expanding and collapsing rows containing children
        - Multiple levels of nesting
    - Rearangeing rows (drag and drop)
    - Moving rows from one parent to another (drag and drop)
- Timeline content 
    - Ability to switch the main content view by passing a custom component
    - Displaying a timeline with custom zoom (year, quarter, week day etc.)
    - Displaying Gantt chart like dependency
    - Displaying many stages per row
    - Dragging and dropping stages withing one row
    - (?) Dragging and dropping stages between rows
    - (?) Filtering rows/stages
    - Scroll using drag
- Passing data to the timeline component from above
- Updating single row or stage on data change
    - Subscribing to websockets for changes
- Colaboration
    - It must be possible for many users to collaborate on this same timeline
    - (?) Virtual scroll
    