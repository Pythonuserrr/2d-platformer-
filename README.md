# 2d-platformer-import pygame

# Initialize pygame
pygame.init()

# Set the screen size
screen = pygame.display.set_mode((800, 600))

# Run the game loop
running = True
while running:
    # Handle events
    for event in pygame.event.get():
        if event.type == pygame.QUIT:
            running = False

    # Update the game state

    # Draw the game
    screen.fill((0, 0, 0))
    pygame.display.flip()

# Clean up
pygame.quit()
