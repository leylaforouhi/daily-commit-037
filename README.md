from datetime import datetime

def current_datetime():
    now = datetime.now()
    return now.strftime("%Y-%m-%d %H:%M:%S")

if __name__ == "__main__":
    print(f"Current date and time: {current_datetime()}")
