1. Background Information
                 
        I. For every simulation attached, I will include in the ReadMe:
                  1. A list of libraries/modules used
                  2. A screenshot from the simulation
                  3. Credit (when necessary)
        II. All of my code, unless otherwise noted, was written in VSCode.
        III. Underneath the credit, there will be a short description of the skills used in creating the corresponding simulation.
   

3. Planet Simulation
   
   Libraries/modules used: Pygame
  <img width="796" alt="Screenshot 2023-11-02 at 2 30 12 AM" src="https://github.com/redcygni/Physics-Simulations/assets/118145890/7b775bf3-4e9b-4004-9583-f3a971d3439d">

   
   I followed this tutorial on youtube: https://www.youtube.com/watch?v=WTLPmUHTPqo&ab_channel=TechWithTim
   
   This simulation primarily utilizes an understanding of computer graphics in python and applied math in python. It utilizes the pygame library for visualization. The math in this simulation is adapted from an understanding of circular motion, orbital mechanics, and Newton's law of universal gravitation. The force of attraction between one planet and all others is calculated using Newton's law of gravitation and then split into its x and y components using trigonometry. The position of the planets is then updated by using these force components along with mass in Newton's second law to calculate acceleration. The simulation works by constantly running on a loop that continuously calculates the force of attraction between all the bodies updates their positions, tracks their positions, and then redraws the objects in their new positions. 
