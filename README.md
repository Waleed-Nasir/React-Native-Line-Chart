# React-Native-Line-Chart


# Usage 

        <View style={{ flex:1 }}>
            <Line 
            valuesTem={[40, 30, 70, 40, 70, 40, 70, 50, 100, 70, 40, 70, 50, 100, 70, 40, 70, 50, 100, 70, 40, 70, 50]}
            valuesHum={[40, 30, 70, 60, 70, 40, 70, 50]}
             />
                    {([...Array(15)]).map((val, i) => (
                      <View key={i} style={{ width: 32, flexDirection: "row", alignItems: "flex-end", position: "absolute",bottom: `${i * 6}%` }}>
                        <Text style={{ marginHorizontal: 2, fontSize: 8, }}>{140-(10*i)}</Text>
                      </View>
                    ))}
                  </View>
