# en-react-app-for-alawaio

You need to create a SPA application for multi-level parking, which will display the current state of the parking space.

## Design [Figma](https://www.figma.com/file/pFMfvwBdK2xPA6defX3ALz/react-app?node-id=0%3A1)

## JSON [file](https://github.com/6apny/en-react-app-for-alawaio/blob/master/data.json)

## Requirements

- Display the level selection. Select any drop-down list.
- Display all parking spaces of the selected level (standard level A). Blocks of 4 parking space each.
- Display the total number of parking spaces available and occupied in the page header.
- The right side consists of two sections: "Info" and "Notifications".
- The sections are changed by pressing the Tab of the corresponding section.
- The left menu duplicates the change of the section in the aside.
- Display the status of the parking space in the right side in the "Info" section. If the location is available, then display the time selection.
- After selecting the time, click Ok to change the status of the selected location to "Reserved" and add a notification to "Notifications" about the change of the status "{location} {status} {time}"
- Pressing the time again-cancels the selection. The status changes to "Available". Also add to "Notifications" a notification about the change of the status "{location} {status} {time}"

