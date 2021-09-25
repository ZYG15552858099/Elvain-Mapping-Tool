# Elvain-Mapping-Tool

## Intruduction

This Grasshopper tools help **YOU** to identify the position relations between Parking Area and Residential Area.Instead of directly showing the coordinates of residential and parking areas in the city, these tools help you understand whether the distribution of residential areas affects the distribution of parking areas in different cities!

## Example

When **YOU** enter the map into **File Path**, you need to bake the important information Caribous pulls out and enter the points and curves in the battery pack below. Rhino generates the texture of the city and shows where the parking area, bicycle parking area and residential area are located
![_I51I9)3R9~XI2Y6QT09_YT](https://user-images.githubusercontent.com/88922796/130340935-a2f28ab9-18c7-4c93-9f09-521961d6f34d.png)
![$8{FC0T`{A$}3%3H7VM}O07](https://user-images.githubusercontent.com/88922796/130340937-048affda-5164-49b6-9243-a4eb09e9ec15.png)

## Use

- Step 1 Creating maps document from **OpenStreetMap**, then load the map file into Grasshopper. Then check for **Parking**, **Apartment** and other research things in **Specify Features** and check the keywords to show them
 ![SQI9OGWN`WY9DHZ6`PJH)}0](https://user-images.githubusercontent.com/88922796/130341173-a28923f5-e906-44e8-b8f6-b1c97fe25842.png)

- Step 2 Bake out the desired points and curves and then identify them into the battery pack in the picture
 ![{R1OA)6@0XU66M8U55(DCN6](https://user-images.githubusercontent.com/88922796/130341178-fefd1975-3816-46b2-96bd-7a053bcbd581.png)

- Step 3 In the red area of the battery pack, right-click and select **Preview on** to display the results
![S 3Q7O%_F@PMMHV7LLZT7AL](https://user-images.githubusercontent.com/88922796/130341181-827babc6-d56a-447d-88d7-2b2c9fc4eb18.png)

## Closest Point

It is also a method to find the distribution law of the parking areas to divide the city into several areas through the closest boundaries.

![B{6CRKC3CC_ 7WWNNFP{6ID](https://user-images.githubusercontent.com/88922796/129523375-bb487c68-d3f4-4e0f-b20e-c90f06db0faf.png)
![F@6 YCN1FGF7YI {C5L 5(6](https://user-images.githubusercontent.com/88922796/129523387-6e59d84e-e465-4664-a730-ab3ca87f664d.png)

# v1.0 Elvain Tool

- After a month of work, the developer have completed the Elvain Tool version 1.0. In this update, the developer has improved the component to extract points and threads from Caribous; Categorize each component and describe its function; Adding a component that can generate the change of elements through the sliding slider to predict the change of different types of parking areas in the future; Adding a UI Page component that digitally visualizes these predicted changes makes it easier for users to see the magnitude of the changes.

## The Third Part

### Time Slider

- The first technology to be added was Time Slider. This part mainly predicts the change rule of the existing urban parking Area and Apartments Area in the future through the location and quantity relationship between them.
![image](https://user-images.githubusercontent.com/88922796/134769852-d0d48386-4353-400b-a795-bc8f071b3d53.png)

- Different from the components in the second part, the components in the third part extract the information of urban parking areas. They show the changes of the types and locations of urban parking areas in the future by changing the number from 0 to 100 on a slider. This slider is similar to a timeline, and the user slides the slider to change the time.
![image](https://user-images.githubusercontent.com/88922796/134770868-3c370e0a-aac5-44e3-979d-b344ac631076.png)

### Changes of Surface Parking Area

- The components in this picture show the transformation of the surface parking area in the future. When the slider number reaches 100, more than 90% of the above-ground parking area will be transformed into underground parking, bicycle parking area and parking buildings.
![image](https://user-images.githubusercontent.com/88922796/134770949-ff6f8a68-5593-44a0-ab34-25d48a42c084.png)

### Legend

- Legend was also created and placed in Rhino to help users quickly identify different types of parking areas.
![image](https://user-images.githubusercontent.com/88922796/134772000-3bd70c4c-5606-4e2a-9f9a-c62ef9f4ad54.png)

### Areas of Parking Area

- The component in this figure is a prediction of the network formed by each of the four parking areas. As the number on the time slider changes from 1 to 100, the network in the above-ground parking area gradually decreases, while the network in the other three parking areas gradually increases.
![image](https://user-images.githubusercontent.com/88922796/134772028-452a20e9-d498-4d7d-994a-5c4ffefb8a18.png)

- This is a map of parking areas in Manila when the number is 1
![image](https://user-images.githubusercontent.com/88922796/134772044-626cf77d-4ef8-4dcd-9cb1-7edd5a6f443e.png)

- This is a map of the parking area in Manila when the number is 100
![image](https://user-images.githubusercontent.com/88922796/134772048-0e29f11e-3ff4-404f-af14-85b18930ccf2.png)

## The Fourth Part

### UI Page Introduction

- The component in this section creates a UI Page in Rhino that shows the ratio of the number of parking Spaces to future changes. The first bar chart shows the current number of four parking areas in a city. The second bar chart shows that the areas of the other three parking areas change with time, except the above-ground parking area.
![image](https://user-images.githubusercontent.com/88922796/134772127-1e3b6a24-5c0c-416c-9993-8835ad2597e7.png)
![image](https://user-images.githubusercontent.com/88922796/134772130-09024960-636c-4fde-b029-958c20e0b6f4.png)

These are the updates to Elvain Tool 1.0. If you find any problems or suggestions while using it, the developer is looking forward to your comments in the Issue section.


