# Supply Chain Management Project – Sharif University of Technology

Supply Chain simulation and transportation optimization project using AnyLogistix, including network modeling, cost analysis, and logistics performance evaluation.

## About This Project

This project models, simulates, and optimizes a real-world supply chain for a yogurt production and distribution company operating across Iran and Azerbaijan. It was completed in three progressive phases as part of a university course at Sharif University of Technology, using AnyLogistics — a professional-grade supply chain simulation platform.

## Why This Project Is Useful

This project demonstrates the full engineering workflow for tackling those problems. Rather than relying on intuition or simple spreadsheet models, it uses simulation and mathematical optimization to make decisions that are grounded in data and validated against uncertainty. The methods used here — discrete-event simulation, inventory policy modeling, vehicle routing optimization, and sensitivity analysis — are the same methods used by supply chain teams at companies like Amazon, Toyota, and Maersk. Working through them in the context of a concrete, realistic case study builds the kind of practical understanding that transfers directly to industry.

## Methods and Tools

The simulation component uses discrete-event modeling, where every shipment, production run, vehicle trip, and inventory check is treated as a time-stamped event that moves the system forward. This captures the timing dependencies and queuing effects that aggregate models miss. The transport optimization component solves a variant of the vehicle routing problem, finding cost-minimizing delivery routes subject to constraints on vehicle load, travel distance, operating hours, and service territories.

All modeling was done in AnyLogistics. Post-processing of optimization outputs — cost aggregation and distance analysis by DC — was done in Microsoft Excel using pivot tables.
