import time

def countdown_stopwatch(seconds):
    while seconds > 0:
        print(f"Time remaining: {seconds} seconds")
        time.sleep(1)
        seconds -= 1
    print("Time's up!")


  
