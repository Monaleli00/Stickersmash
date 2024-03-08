import { StatusBar } from "expo-status-bar";
import { StyleSheet, Text, View, Image } from "react-native";
import { AntDesign } from "@expo/vector-icons";

export default function App() {
  return (
    <View style={styles.container}>
      <View style={styles.header}>
        <Image source={require("./Id.jpg")} style={styles.profilePicture} />
        <View style={styles.detailsBox}>
          <Text style={styles.nameText}>Amohelang Monaleli</Text>
          <Text style={styles.timeText}>10 hrs</Text>
        </View>
      </View>
      <View style={styles.postBody}>
        <Text style={styles.postMessage}>This is the new me</Text>
        <Image source={require("./Id.jpg")} style={styles.postImage} />
      </View>
      <View style={styles.footer}>
        <View style={styles.iconsRow}>
          <AntDesign name="like2" size={24} color="black" style={styles.icon} />
          <Text style={styles.iconText}>62 Likes</Text>
        </View>
        <View style={styles.iconsRow}>
          <AntDesign
            name="message1"
            size={24}
            color="black"
            style={styles.icon}
          />
          <Text style={styles.iconText}>Comment</Text>
        </View>
        <View style={styles.iconsRow}>
          <AntDesign
            name="forward"
            size={24}
            color="black"
            style={styles.icon}
          />
          <Text style={styles.iconText}>Share</Text>
        </View>
      </View>
      <View style={styles.threeDots}>
        <AntDesign name="ellipsis1" size={24} color="black" />
      </View>
      <StatusBar style="auto" />
    </View>
  );
}

const styles = StyleSheet.create({
  container: {
    flex: 1,
    backgroundColor: "white",
    paddingTop: 20,
  },
  header: {
    flexDirection: "row",
    alignItems: "center",
    marginBottom: 10,
  },
  profilePicture: {
    width: 50,
    height: 50,
    borderRadius: 25,
    marginRight: 10,
  },
  detailsBox: {},
  nameText: {
    color: "black",
    fontSize: 18,
    fontFamily: "AmaticSC-Regular",
  },
  timeText: {
    color: "black",
    fontSize: 12,
    fontFamily: "AmaticSC-Regular",
  },
  postBody: {
    marginBottom: 10,
  },
  postMessage: {
    color: "black",
    fontSize: 16,
    fontFamily: "AmaticSC-Regular",
    marginBottom: 5,
  },
  postImage: {
    width: "100%",
    height: 200,
  },
  footer: {
    flexDirection: "row",
    justifyContent: "space-between",
    alignItems: "center",
  },
  iconsRow: {
    flexDirection: "row",
    alignItems: "center",
    marginRight: 10,
  },
  icon: {
    marginRight: 5,
  },
  iconText: {
    color: "black",
    fontSize: 14,
    fontFamily: "AmaticSC-Regular",
  },
  threeDots: {
    position: "absolute",
    top: 10,
    right: 10,
    padding: 10,
  },
});
