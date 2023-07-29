import time

def blinking_hello():
    while True:
        print("\033[1;32;40mHello, dunia!\033[0m", end="\r")
        time.sleep(0.5)
        print("                ", end="\r")
        time.sleep(0.5)

if __name__ == "__main__":
    blinking_hello()
