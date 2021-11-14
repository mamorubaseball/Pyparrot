from pyparrot.Anafi import Anafi
anafi = Anafi(drone_type="Anafi", ip_address="192.168.42.1")
print("connecting")
success = anafi.connect(10)
anafi.safe_land(5)
anafi.disconnect()
