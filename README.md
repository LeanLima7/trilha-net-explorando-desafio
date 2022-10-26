# DIO - .NET Trail - Exploring the C# language

[Digital Innovation One](https://www.dio.me/?ref=RE6NDV822B)

## Project challenge

For this challenge, I needed to use the knowledge acquired in the module exploring the C# language, from DIO's .NET track.

## Context
In this challenge, the situation created was a simulation where I was hired to build a hosting system, which could be used to make a reservation at a hotel. For that I've isied the Person class, which represents the guest, the Suite class, and the Reservation class, which made a relationship between them.

This program correctly calculates the values ​​of the methods of the Reservation class, which bring the number of guests and the daily rate, granting a 10% discount if the reservation is for a period longer than 10 days.

## Rules and validations
1. It must not be possible to book a suite with a capacity smaller than the number of guests. Example: If it is a suite capable of hosting 2 people, then when passing 3 guests it should return an exception.
2. The GetQuantidadeHospedes method of the Reservation class must return the total number of guests, while the CalculateValorDaily method must return the daily rate (Booked days x daily rate).
3. If a reservation is made equal to or greater than 10 days, a 10% discount on the daily rate must be granted.

![Class Diagram](diagrama_classe_hotel.png)

## Solution
The code was half finished, I continued obeying the rules described above, so that in the end, we had a working program.

 [Certificate: 📜](https://www.dio.me/en/certificate/4E02AD64/share)