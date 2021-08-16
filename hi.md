    useLayoutEffect(() => {
        navigation.setOptions({
            title: "JookGroo",
            headerStyle: { backgroundColor: "#fff" },
            headerTitleStyle: { color: "black" },
            headerTintColor: "black",
            headerLeft: () => (
                <View style={{ marginLeft: 20 }}>
                    <Avatar rounded source={{ uri: auth?.currentUser?.photoURL }} />
                </View>
        )
        })
    }, [])
    
    not working help me please respond
