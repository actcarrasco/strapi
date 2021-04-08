# Strapi application
<Pressable onPress={() => navigation.navigate("LocationSelector")}>
          <View pointerEvents="none">
            <Input
              autoFocus={true}
              autoCorrect={false}
              numberOfLines={1}
              keyboardShouldPersistTaps="always"
              inputStyle={stylesInput.TextInputStyle}
              inputContainerStyle={stylesInput.inputContainerStyle}
              value={address}
              onPress={() => navigation.navigate("LocationSelector")}
              leftIcon={
                <MaterialCommunityIcons
                  name="map-marker"
                  style={{ marginBottom: 5, height: 25 }}
                  color="#4442d6"
                  size={25}
                  onPress={() => navigation.navigate("LocationSelector")}
                />

              }
            />
          </View>
        </Pressable>
