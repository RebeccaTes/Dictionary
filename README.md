# Dictionary
def main():
    spacecraft = {"Name": "James Webb Space Telescope", "distance": 163}
    spacecraft.update({"distance": 0.01, "orbit": "Sun"})
    print(creat_report(spacecraft))

def creat_report(spacecraft):
    return f"""
    =========== Report ===========
    
    Name: {spacecraft.get("Name", "Unknown")}
    Distance: {spacecraft.get("distance", "Unknown")} AU
    Orbit: {spacecraft.get("orbit", "Unknown")}
    
    ===============================
    """
main()
