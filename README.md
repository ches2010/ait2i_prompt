# ait2i_prompt
ai绘图prompt

```json
{
  "image_metadata": {
    "format": "JPEG",
    "orientation": "portrait",
    "dominant_colors": ["beige", "pink", "white", "brown"]
  },
  "subject_description": {
    "person": "A young woman with long, dark, wavy hair.",
    "pose": "She is squatting or crouching next to a low brick wall/window sill. Her body is angled slightly to the right, but she is looking directly at the camera with a gentle smile.",
    "clothing": {
      "top": "A fitted, beige or light taupe ribbed knit cardigan with buttons down the front and three-quarter length sleeves.",
      "bottom": "A pink lace pencil skirt or midi skirt.",
      "footwear": "Nude or beige high-heeled pumps featuring a bow detail on the toe.",
      "accessories": "She is wearing a delicate gold necklace and thin bracelets on both wrists."
    }
  },
  "background_environment": {
    "location": "Outdoors, likely an urban street or building exterior.",
    "elements": [
      "A plain, light cream-colored wall behind her.",
      "A dark brown window frame on the right side.",
      "A window sill made of red bricks.",
      "Paved ground with textured tiles."
    ]
  }
}
```

```json
{
  "image_data": {
    "id": "img_20230815_001",
    "format": "jpeg",
    "dimensions": {
      "width": 1080,
      "height": 1620
    },
    "description": "A young woman posing outdoors in a park setting during golden hour. She is leaning back against a large tree trunk with her eyes closed, enjoying the sunlight. She holds a pair of sunglasses up in the air with her right hand. She is wearing a yellow camisole top, white pleated shorts, white socks, and pink sneakers.",
    "scene_elements": [
      "Park",
      "Tree trunk with white paint at the base",
      "Grassy ground",
      "Paved path",
      "Background trees"
    ],
    "subject_attributes": {
      "pose": "Leaning against tree, arm raised",
      "expression": "Smiling, eyes closed, relaxed",
      "attire": {
        "top": "Yellow tank top with orange trim",
        "bottom": "White shorts",
        "footwear": "Pink running shoes",
        "accessories": "Sunglasses held in hand, bracelet on wrist"
      }
    },
    "lighting": "Natural sunlight, warm tone, casting shadows on the grass",
    "mood": "Cheerful, summery, relaxed, carefree"
  }
}
```

```json
{
  "image_description": "A young woman sitting outdoors on a wooden park bench.",
  "subject": {
    "gender": "female",
    "pose": "sitting sideways, smiling and looking to the left",
    "clothing": {
      "headwear": "khaki baseball cap",
      "top": "yellow tank top with reddish-brown trim",
      "bottom": "white shorts"
    },
    "accessories": [
      "necklace",
      "watch or bracelet on left wrist",
      "red string bracelet on right wrist"
    ]
  },
  "setting": {
    "location": "park or garden",
    "background_elements": [
      "trees",
      "grass",
      "fallen leaves",
      "paved path in distance"
    ],
    "lighting": "natural daylight, soft shadows"
  },
  "mood": "casual, cheerful, summer vibe"
}
```

```json
{
  "image_data": {
    "subject": "Young woman (appearing to be Yang Chaoyue)",
    "clothing": {
      "top_outer": "Black blazer jacket",
      "top_inner": "Black lace corset/bustier",
      "bottom": "Black high-waisted pants or skirt"
    },
    "accessories": [
      "Wire-rimmed glasses",
      "Pearl earrings"
    ],
    "hairstyle": "Dark hair pulled back/updo",
    "action": "Leaning against a white door frame with one hand raised and the other in pocket",
    "background": "White wall and white door with silver handle",
  }
}
```

```json
{
  "image_description": "A vertical studio portrait of a young woman with long, straight black hair. She is posing in a whimsical, pastel-colored setting.",
  "subject_details": {
    "person": "Young Asian female model",
    "hair": "Long, straight, dark hair parted in the middle",
    "makeup": "Soft pink blush on cheeks, natural lip color",
    "expression": "Calm, looking slightly off-camera to the left"
  },
  "attire_and_accessories": {
    "dress": "Pale pink or champagne-colored satin halter-neck dress with a tie at the neck",
    "eyewear": "Clear-framed glasses decorated with small colorful flowers on the temples",
    "jewelry": "Silver rings on her fingers, a small flower accessory attached to her upper left arm"
  },
  "environment_and_props": {
    "seating": "Sitting on a fluffy, deep magenta/purple faux fur rug or cushion",
    "background_objects": [
      "Large purple fabric rose on the left",
      "Large yellow/green star-shaped plush object with rhinestones on the right",
      "Another purple fabric flower near her hip"
    ],
    "flooring": "A light green textured surface beneath the purple fur"
  },
  "lighting_and_mood": {
    "lighting": "Soft, diffused studio lighting",
    "color_palette": "Pastel pinks, purples, greens, and white",
    "mood": "Dreamy, ethereal, soft, fashion editorial"
  }
}
```

```json
{
  "image_description": "A young woman posing indoors, possibly at an event or photoshoot.",
  "subject": {
    "gender": "Female",
    "hair": "Long, straight, black hair",
    "accessories": [
      "Glasses",
      "Ring on right hand"
    ],
    "pose": "Standing with right hand on hip, looking slightly to the right"
  },
  "clothing": {
    "item": "Dress",
    "color": "Pale pink / Light lavender",
    "style": "Sleeveless, halter neck with a bow tie at the collar",
    "length": "Mini dress"
  },
  "background": {
    "setting": "Indoors, likely a studio or event space",
    "elements": [
      "White curtains in the background",
      "Silver star-shaped balloon",
      "Yellow balloon",
      "Purple carpet/rug with white dots",
      "Metal shelving unit"
    ]
  },
  "other_people": [
    {
      "description": "Man holding a camera on a tripod",
      "position": "Background right"
    },
    {
      "description": "Man standing with arms crossed",
      "position": "Background far right"
    }
  ],
  "objects": [
    {
      "name": "Stuffed animal",
      "description": "Brown teddy bear sitting on the floor",
      "position": "Bottom left"
    },
    {
      "name": "Chair",
      "description": "Glass chair with colorful fabric/bags on it",
      "position": "Left side"
    }
  ]
}
```

```json
{
  "image_analysis": {
    "subject": "一位年轻女性（疑似中国女演员徐璐）",
    "attire": {
      "dress": "白色抹胸短裙，材质带有光泽感（类似缎面或丝绸），肩部设计有轻盈的薄纱飘带。",
      "shoes": "白色细高跟凉鞋，露趾款式。",
      "headwear": "银色镶钻皇冠头饰。"
    },
    "pose_and_action": "女子身体微微侧向镜头，左手轻扶黑色门的把手，似乎正在开门或倚靠。右腿微微抬起交叉在左腿前，呈现出一种优雅且略带动感的姿态。目光向下，神情显得有些慵懒或沉思。",
    "setting_and_lighting": {
      "background": "深色（黑色）的门和墙面，环境极简。",
      "lighting": "聚光灯效果，光线主要集中在人物身上，形成强烈的明暗对比，突出了人物的轮廓和皮肤质感。"
    },
  }
}
```

```json
{
  "image_description": "一张高质量的人物肖像图，展示了一位身着紫色礼服的年轻女性坐在室内。",
  "visual_elements": {
    "character": {
      "appearance": "长发黑直发，皮肤白皙，五官精致，眼神平静地注视着前方。",
      "pose": "侧身坐在床沿或类似的家具上，左手支撑身体，右手搭在旁边的木质台面上，双腿交叠，展示出修长的腿部线条。"
    },
    "clothing": {
      "color": "深紫色",
      "style": "深V领吊带长裙，材质看起来轻盈飘逸（类似丝绸或雪纺）。",
      "details": [
        "胸前和腰部有金色的金属质感装饰或刺绣。",
        "裙子侧面有高开叉设计。",
        "背部似乎有同色系的薄纱披肩或飘带垂下。"
      ]
    },
    "accessories": [
      "头顶佩戴着精致的银色或金属质感的头饰/皇冠。",
      "颈部佩戴着细链条项链。",
      "右大腿处有一个明显的蕾丝花纹图案（可能是纹身或蕾丝腿环）。"
    ],
    "background": {
      "setting": "室内卧室场景",
      "elements": [
        "左侧有明亮的窗户透入光线。",
        "身后有深红色的窗帘。",
        "旁边有木质的家具结构（可能是床头板或屏风）。"
      ]
    }
  },
  "style": "写实风格数字绘画 (Digital Art) 或 高精细度3D渲染，具有典型的现代网络插画审美。",
}
```

```json
{
  "image_description": {
    "subject": {
      "gender": "female",
      "hair": "long, straight, black",
      "expression": "gentle smile, looking at camera",
      "makeup": "natural, light makeup"
    },
    "attire": {
      "type": "black slip dress or camisole top",
      "material": "appears to be satin or silk (shiny texture)",
      "style": "sleeveless, low neckline",
      "accessories": [
        "delicate necklace"
      ]
    },
    "setting": {
      "location": "indoors, likely a high-rise building",
      "specific_place": "restaurant, bar, or hotel room",
      "background_view": "nighttime city skyline with blurred lights (bokeh effect)"
    },
    "environment_details": {
      "window": "large glass window, reflections visible on the left side",
      "foreground_objects": "a QR code stand is partially visible in the bottom left corner"
    },
    "lighting_and_mood": {
      "lighting": "indoor ambient lighting, soft on the face",
      "mood": "elegant, relaxed, urban nightlife"
    }
  }
}
```

```json
{
  "status": "success",
  "data": {
    "description": "一张充满氛围感的人像照片，一位年轻女性坐在窗边，阳光洒在她身上。",
    "subject": {
      "person": "年轻女性",
      "hair": "深色长发，扎在脑后，留有空气刘海",
      "expression": "面带微笑，眼神柔和地看向右下方，神情恬静",
      "clothing": [
        "米白色粗针织毛衣（Oversize风格，露肩设计）",
        "内搭红色细肩带背心（隐约可见）"
      ],
      "details": "毛衣下摆处有黑色字母印花，部分可见为 'ASEMEN'"
    },
    "environment": {
      "location": "室内窗边",
      "background": "木质窗框，窗外有明亮的自然光和模糊的绿植/建筑轮廓",
      "lighting": "自然侧光，光线从右侧窗户射入，照亮了人物的面部和毛衣纹理，营造出温暖柔和的氛围"
    },
    "metadata": {
      "mood": "温馨、慵懒、文艺"
    }
  }
}
```

```json
{
  "image_description": {
    "subject": "A stylized, semi-realistic 3D animated character of a young woman.",
    "appearance": {
      "hair": "Short, dark brown bob cut.",
      "face": "Soft features, smiling with eyes closed, flushed cheeks, freckles.",
      "outfit": "A light pink, deep V-neck one-piece swimsuit."
    },
    "pose_and_action": "She is sitting cross-legged on the sand. Her right arm is extended forward holding a drink towards the viewer, while her left hand is raised in a waving gesture.",
    "held_object": "A clear plastic cup filled with an orange beverage (likely juice or cocktail) containing ice and a white straw.",
    "setting": {
      "location": "A sandy beach near the ocean.",
      "time_of_day": "Golden hour (sunset or sunrise), indicated by the warm, bright sunlight reflecting off the water and sand.",
      "background_elements": [
        "Gentle ocean waves in the distance.",
        "Large beige beach umbrellas providing shade.",
        "Wooden lounge chairs."
      ]
    },
    "visual_style": "High-quality 3D rendering, resembling characters from modern animation or video games (like C4D or Blender art). Soft lighting and textures.",
  }
}
```

```json
{
  "image_url": "https://p1.zsdimg.com/aicrop/300_400/pic-3786579982709.jpg~tplv-yh8z4y2kx4-image.image",
  "description": "A young woman posing indoors, likely in a cafe or restaurant.",
  "attributes": {
    "person": {
      "gender": "Female",
      "hair": "Long, dark brown/black hair with bangs",
      "expression": "Neutral, looking directly at the camera"
    },
    "clothing": {
      "style": "JK Uniform / School Girl Style",
      "top": "White short-sleeved button-up shirt",
      "accessory": "Dark grey/black bow tie",
      "bottom": "Dark grey plaid pleated mini skirt",
      "legwear": "Black over-the-knee socks"
    },
    "pose": {
      "action": "Standing and leaning slightly against a wooden table/surface",
      "hands": "Both hands are raised near her shoulders/hair, gently holding strands of hair"
    },
    "environment": {
      "location": "Interior space with warm lighting",
      "background_elements": [
        "Large concrete pillar on the left",
        "Wooden ceiling and walls",
        "Yellow leather booth seating",
        "Wooden chairs and tables",
        "Red fire extinguisher visible in the bottom left corner",
        "Reception area visible in the far background"
      ]
    },
  }
}
```

```json
{
  "image_data": {
    "description": "一位年轻女性在室内拍摄的半身照，她正对着镜头眨眼摆姿势。",
    "subject": {
      "gender": "Female",
      "hair": "Long, wavy dark brown hair with bangs",
      "expression": "Playful wink with one eye closed",
      "pose": "Leaning slightly against a chair, left hand making a gesture near chin, right hand resting on the chair seat."
    },
    "attire": {
      "top": "White short-sleeved blouse with a dark collar detail",
      "bottom": "Grey plaid pleated mini-skirt (JK uniform style)",
      "accessories": ["Bracelets on left wrist", "Gold bangle on right wrist"]
    },
    "environment": {
      "setting": "Indoors, likely a cafe or lounge area",
      "background_elements": [
        "Yellow leather booth seat on the left",
        "Wooden wall with a pegboard design on the right",
        "Shopping bags (white and green) hanging on the wall hooks",
        "Recessed ceiling light"
      ]
    }
  }
}
```

```json
{
  "image_metadata": {
    "subject": "Young Woman",
    "setting": "Outdoor / Garden Path",
    "lighting": "Bright Sunlight",
    "watermark": "知乎 @高校校园星探"
  },
  "visual_elements": {
    "person": {
      "action": "Standing, posing with one hand raised to shield eyes from the sun",
      "hair": "Long brown hair, partially tied back with a large white scrunchie",
      "expression": "Soft smile, looking at camera"
    },
    "clothing": {
      "inner_wear": "White lace mini dress with a sweetheart neckline and a front tie detail",
      "outer_wear": "Light blue, sheer long-sleeved cardigan or shrug",
      "accessories": [
        "Delicate necklace",
        "Small beige/cream handbag held in right hand"
      ]
    },
    "background": {
      "vegetation": "Dense green hedge or bushes filling most of the background",
      "ground": "Grey paved walkway with a herringbone brick pattern"
    }
  },
  "style": {
    "aesthetic": "Fresh, summery, K-fashion style",
    "color_palette": [
      "White",
      "Light Blue",
      "Green",
      "Beige"
    ]
  }
}
```

```json
{
  "image_url": "https://p1.zhimg.com/50/v2-b8c7d3f0b9e5a1c7d4e6f8a9b0c1d2e3_720w.jpg?source=1940ef5c",
  "description": "A young woman sitting in a cafe, wearing a white dress and light cardigan.",
  "details": {
    "subject": {
      "gender": "female",
      "hair": "brown, long, tied back with a large white scrunchie",
      "clothing": [
        "white lace dress",
        "light blue/white sheer cardigan"
      ],
      "pose": "sitting on a beige sofa, left hand touching her face, right hand resting near a bag"
    },
    "setting": {
      "location": "cafe or restaurant",
      "background": "large window view of green trees and a white van outside, dark wooden slats on the wall"
    },
    "objects": [
      {
        "item": "iced coffee",
        "position": "on the round wooden table"
      },
      {
        "item": "small cake",
        "position": "on a white plate on the table"
      },
      {
        "item": "silver tea set",
        "position": "on the table"
      },
      {
        "item": "white handbag (Chanel)",
        "position": "next to the woman on the sofa"
      }
    ]
  }
}
```

```json
{
  "image_description": "A young woman posing indoors, likely in a cafe or restaurant. She is wearing a school uniform style outfit consisting of a white short-sleeved blouse with a dark bow tie, a grey plaid pleated skirt, and black over-the-knee socks. She has long, wavy dark hair and is making a 'peace' sign gesture with her right hand near her face. The background features wooden paneling, a leather booth seat, wooden chairs, and a red fire extinguisher.",
  "tags": [
    "portrait",
    "fashion",
    "JK uniform",
    "sailor suit",
    "plaid skirt",
    "knee-high socks",
    "cafe",
    "indoor photography"
  ],
  "metadata": {
    "setting": "Indoors",
    "lighting": "Warm ambient light",
  }
}
```

```json
{
  "image_analysis": {
    "subject": {
      "gender": "female",
      "appearance": "young woman with long wavy dark hair, some braided",
      "expression": "looking directly at the camera with a soft, confident gaze",
      "pose": "leaning slightly forward, hand resting near her cheek"
    },
    "attire_and_accessories": {
      "headwear": "wide-brimmed brown cowboy hat with a leather band and metal embellishments (possibly a steer skull)",
      "top": "sparkling gold/metallic sleeveless top with white lace trim underneath",
      "jewelry": [
        "multiple layered necklaces (gold chains, beads, pendants)",
        "large hoop earrings",
        "gold bracelet on the right wrist",
        "hair accessory in the braid"
      ]
    },
    "makeup": {
      "eyes": "defined eyeliner and mascara",
      "lips": "orange-brown lipstick",
      "face": "contoured cheeks, beauty mark near the left eye"
    },
    "setting_and_lighting": {
      "background": "blurred red background with indistinct white text/patterns on the left, darker area on the right",
      "lighting": "warm, studio lighting highlighting the subject's face and the texture of the clothing",
      "mood": "glamorous, western-chic, stylish"
    },
    "metadata": {
      "estimated_identity": "Likely Chinese actress/model Zhang Yuxi (张予曦) based on facial features and style"
    }
  }
}
```

```json
{
  "image_info": {
    "subject": "A young woman, likely a celebrity (resembling Zhang Yuxi), dressed in formal attire.",
    "attire": {
      "dress_type": "White strapless gown / Bridal style",
      "details": [
        "Intricate feather texture on the skirt",
        "Pearl and bead embellishments on the bodice",
        "Sheer, sparkling veil covering the head"
      ]
    },
    "appearance": {
      "hair": "Dark, pulled back sleekly",
      "makeup": "Glamorous look with defined eye makeup and reddish lipstick"
    },
    "background": {
      "setting": "Indoors, possibly an event venue",
      "lighting": "Bokeh effect with colorful blurred lights in the distance"
    },
  }
}
```

```json
{
  "image_description": "A young woman sitting by a large window in what appears to be a cafe or restaurant.",
  "subject": {
    "gender": "female",
    "hair": "Black hair pulled back into a low ponytail",
    "expression": "Gentle smile, looking directly at the camera",
    "pose": "Sitting on a curved wooden bench, body angled slightly towards the right"
  },
  "clothing": {
    "top": {
      "type": "Ribbed sleeveless tank top",
      "color": "Cream or light beige",
      "details": "Features a black graphic print on the chest with a crown and stylized text"
    },
    "bottom": {
      "type": "Denim mini skirt",
      "color": "Light washed green/blue"
    }
  },
  "environment": {
    "setting": "Indoor space with floor-to-ceiling windows",
    "lighting": "Natural daylight streaming in from the windows",
    "background_details": [
      "Large windows revealing an outdoor scene with trees and buildings",
      "Curved wooden bench seat along the wall",
      "Wall-mounted light fixture with a spherical bulb",
      "Beige tote bag with black lettering (partially visible 'NO') resting on the bench next to her"
    ]
  },
}
```

```json
{
  "image_analysis": {
    "subject": "Young Asian woman (likely celebrity Zhang Ruonan)",
    "attire": {
      "top": "White ribbed V-neck cardigan with buttons",
      "bottom": "Black pants or skirt (partially visible)"
    },
    "pose": "Standing with arms crossed, looking off to the right side",
    "hair": "Long, wavy dark brown hair, parted slightly off-center",
    "expression": "Calm, gentle smile, soft gaze",
    "lighting": "Backlit with strong sunlight creating a halo effect on the hair and lens flares",
    "background": "Blurred blue sky or backdrop with bright white light areas",
  }
}
```

```json
{
  "image_description": {
    "subject": "A young woman, likely the Chinese actress Zhao Lusi",
    "pose": "Close-up portrait, looking directly at the camera with a soft expression. Her left hand is raised gently touching her neck/collarbone area.",
    "appearance": {
      "hair": "Dark brown hair pulled back into a low ponytail, with some loose strands framing the face.",
      "makeup": "Elegant makeup featuring pinkish eyeshadow, defined eyeliner, and glossy pink lips. Her skin appears flawless and glowing.",
      "attire": "Wearing a light pink strapless or halter-neck top/dress."
    },
    "jewelry_and_accessories": [
      {
        "item": "Earrings",
        "description": "Long, dangling chandelier earrings featuring large pink/purple gemstones surrounded by diamonds."
      },
      {
        "item": "Necklace",
        "description": "An elaborate necklace matching the earrings, featuring pink and green gemstones set in gold."
      },
      {
        "item": "Watch",
        "description": "A luxury watch on the left wrist with a bezel encrusted with multi-colored gemstones (pink, yellow, purple) and a light pink strap."
      }
    ],
    "lighting_and_background": {
      "lighting": "Soft, studio lighting highlighting her face and jewelry.",
      "background": "Neutral, out-of-focus beige/grey background."
    },
  }
}
```

```json
{
  "image_analysis": {
    "subject": {
      "gender": "female",
      "hair": "long, black, wavy",
      "pose": "sitting/crouching on a hay bale, knees bent, head tilted down slightly in a contemplative manner",
      "expression": "serene, pensive, looking downward"
    },
    "attire": {
      "dress": "black sleeveless dress with subtle texture or sequins",
      "shoes": "black high-heeled sandals with straps",
      "accessories": "delicate necklace visible"
    },
    "environment": {
      "location": "outdoor field",
      "props": "large round hay bales",
      "background": "dark blue twilight sky, silhouette of distant hills or trees"
    },
    "lighting_and_mood": {
      "lighting": "dramatic, spotlight effect on the subject against a darker background",
      "color_palette": "deep blues, blacks, warm skin tones, golden straw",
      "atmosphere": "elegant, mysterious, moody, sophisticated"
    },
  }
}
```

```json
{
  "image_info": {
    "subject": "Young woman",
    "viewpoint": "Side profile (facing right)",
    "appearance": {
      "hair": "Long, wavy, dark brown hair with bangs",
      "skin_tone": "Pale/Fair",
      "facial_features": "Delicate features, visible eyelashes and lips"
    },
    "attire": {
      "type": "Evening gown / Dress",
      "color": "Nude/Beige base with gold embellishments",
      "details": "Intricate gold sequin or bead embroidery, sleeveless/designed to show shoulders"
    },
    "pose": {
      "body_position": "Standing sideways",
      "hand_action": "Right hand gently resting near the collarbone/chest area"
    },
    "environment": {
      "background": "Blurred green foliage/trees",
      "lighting": "Soft, natural lighting",
      "location_type": "Outdoor setting"
    },
  }
}
```

```json
{
  "image_description": {
    "subject": "A young woman standing outdoors on a balcony.",
    "attire": {
      "top": {
        "inner_layer": "A white, ribbed halter-neck crop top with a keyhole cutout at the chest.",
        "outer_layer": "A sheer, long-sleeved light cream or off-white cardigan/shrug worn over the top."
      },
      "bottom": "A high-waisted, pleated mini skirt featuring a blue-grey and white plaid (tartan) pattern.",
      "accessories": "None clearly visible, though she appears to be holding a thin pole or umbrella handle in her right hand."
    },
    "pose_and_action": {
      "left_hand": "Raised near shoulder height, palm facing forward, fingers spread slightly as if waving or gesturing 'stop'."
    },
    "setting": {
      "location": "An outdoor balcony or terrace with a metal railing.",
      "background": "A bright blue sky with scattered white clouds. Some city buildings are faintly visible in the lower background."
    },
    "lighting": "Natural daylight, casting soft shadows, suggesting a sunny day."
  }
}
```

```json
{
  "image_description": "一位年轻女性坐在白色的毛绒家具上",
  "subject": {
    "appearance": "年轻女性，皮肤白皙，棕色长发随意束起，几缕发丝垂在脸颊旁",
    "expression": "表情平静温柔，眼神直视镜头",
    "pose": "身体放松地向后倚靠，双腿弯曲，双手自然放置"
  },
  "attire": {
    "dress": "米白色针织材质的细吊带连衣裙，带有褶皱设计",
    "socks": "白色罗纹针织长筒袜"
  },
  "environment": {
    "furniture": "白色的毛绒懒人沙发或豆袋椅",
    "background": "简洁的浅色墙壁",
    "lighting": "柔和温暖的自然光，投射出清晰的影子，营造出慵懒的氛围"
  },
}
```

```json
{
  "image_description": "A fashion shot of a person wearing a chic winter outfit.",
  "outfit_details": {
    "outerwear": {
      "type": "Jacket / Blazer",
      "material": "Textured fabric with shimmer/glitter finish",
      "features": [
        "Faux fur collar",
        "Faux fur cuffs",
        "Single button closure visible",
        "Open front style showing black lining"
      ],
      "color": "Champagne Gold / Beige"
    },
    "top": {
      "type": "Tube Top / Crop Top",
      "pattern": "Cable knit",
      "fit": "Form-fitting",
      "color": "Cream / Off-white"
    },
    "bottom": {
      "type": "Mini Skirt",
      "pattern": "Cable knit (matching the top)",
      "fit": "High-waisted, bodycon",
      "hemline": "Ribbed hem"
    }
  },
  "visual_elements": {
    "lighting": "Soft, indoor lighting",
    "background": "White door frame, glimpse of a room with a lamp in the background",
    "pose": "Standing, hand resting near the shoulder/chest area"
  },
  "style_tags": [
    "Winter Fashion",
    "Chic",
    "Elegant",
    "Matching Set",
    "Texture Mix"
  ]
}
```

```json
{
  "image_content": {
    "subject": "一位长发女性（外观特征类似演员刘亦菲）",
    "appearance": {
      "hair": "黑色长直发，自然披散",
      "face": "妆容精致，神情冷艳",
      "skin_tone": "白皙"
    },
    "outfit": {
      "upper_body": {
        "inner_wear": "黑色低胸吊带背心",
        "outer_wear": "黑色宽松开衫/薄外套，采用露肩披挂式穿法"
      },
      "lower_body": "蓝色高腰阔腿牛仔裤，裤型宽松",
      "footwear": "黑色尖头高跟鞋"
    },
    "accessories": [
      "金色粗链条项链",
      "右手腕佩戴细手链"
    ],
    "pose": "全身照，身体微侧，左手插在裤兜中，右手自然下垂，目光直视镜头",
    "background": "纯浅蓝色背景，典型的时尚摄影棚风格",
  }
}
```

```json
{
  "image_content": {
    "subject": "女性 (看起来像是刘亦菲)",
    "attire": {
      "upper_body": "白色宽松长袖衬衫",
      "lower_body": "浅蓝色高腰阔腿牛仔裤",
      "footwear": "银色高跟凉鞋",
      "accessories": "长款耳坠"
    },
    "pose": "站立姿势，一手轻抓衣摆，身体微微侧倾",
    "hairstyle": "黑色长卷发，带有动感",
    "background": "纯白色/浅灰色摄影棚背景",
    "style": "时尚写真，简约大气"
  }
}
```

```json
{
  "image_description": {
    "subject": {
      "gender": "female",
      "appearance": "A young woman with long, straight black hair and fair skin. She has a serious, confident expression and is looking directly at the camera.",
      "identity_resemblance": "Resembles Chinese actress Liu Yifei"
    },
    "outfit": {
      "top_outer": "A light blue or white translucent button-down shirt worn open and tied in a knot at the waist/midriff, exposing the stomach.",
      "top_inner": "A dark brown or black spaghetti strap camisole/tank top.",
      "bottoms": "Dark grey or faded black denim jeans."
    },
    "accessories": [
      "Long, dangling silver earrings.",
      "A delicate gold necklace with a small pendant."
    ],
    "setting_and_lighting": {
      "background": "A blurred, bright background consisting of light blues and whites, suggesting an outdoor setting like a sky or body of water.",
      "lighting": "Soft, natural daylight that highlights the subject's face and hair."
    },
    "style": "Fashion photography, casual chic, modern aesthetic."
  }
}
```

```json
{
  "image_description": "一张年轻女性的自拍照，采用室内自然光拍摄。",
  "details": {
    "subject": "年轻女性，黑发及肩，发丝略显凌乱自然。",
    "attire": "穿着白色细吊带背心（crop top）。",
    "features": "皮肤白皙，妆容清淡自然，佩戴着小巧的金色耳环。锁骨明显。",
    "pose_expression": "头部微侧，眼神直视镜头，表情平静带有一丝慵懒感。",
    "lighting": "强烈的自然光从画面左侧射入，造成左侧背景过曝，光线柔和地打在人物面部和身上。",
    "background": "简约的室内环境，可见白色的墙壁和右侧灰色的枕头，推测是在卧室床上。"
  }
}
```

```json
{
  "image_description": {
    "subject": "A young woman with long, dark wavy hair.",
    "pose": "She is sitting in a relaxed pose on a dark, upholstered armchair. Her left leg is bent and raised slightly, while her right arm rests along the arm of the chair. She is looking towards the camera with a soft expression.",
    "attire": "She is wearing a silky, pale yellow or gold slip dress (camisole style) with thin straps. The fabric appears loose and draped.",
    "accessories": "She is wearing a delicate bracelet on her right wrist and a thin anklet or chain on her left ankle.",
    "setting": "The background suggests an indoor setting with somewhat dim, moody lighting, giving it a cinematic or vintage feel. There is a piece of white lace fabric visible in the bottom left corner.",
    "tone": "Elegant, alluring, soft, and intimate."
  },
}
```

```json
{
  "status": "success",
  "message": "Image analysis data returned below.",
  "data": {
    "subject": {
      "person": "Asian female model (resembles Liu Yifei)",
      "hair": "Long, dark, wavy hair",
      "accessories": [
        "Drop earrings"
      ]
    },
    "outfit": {
      "type": "Casual Chic / Denim on Denim",
      "items": [
        {
          "item": "Denim Jacket",
          "color": "Dark Blue / Blackish Blue",
          "details": "Oversized, unbuttoned, draped off one shoulder, decorative stitching/fringe on lapels"
        },
        {
          "item": "Top",
          "color": "White / Cream",
          "details": "Tank top or camisole, v-neckline"
        },
        {
          "item": "Jeans",
          "color": "Dark Blue",
          "details": "High-waisted, straight-leg or slight flare, prominent front pockets"
        },
        {
          "item": "Shoes",
          "color": "Black",
          "details": "Heeled boots or pumps (partially visible)"
        }
      ]
    },
    "pose_and_expression": {
      "pose": "Standing tall, left hand resting on hip, right arm hanging loosely",
      "expression": "Confident, direct gaze at the camera, neutral lips"
    },
    "background": {
      "color": "Light blue to white gradient",
      "lighting": "Bright, studio lighting creating soft shadows"
    }
  }
}
```

```json
{
  "image_info": {
    "subject": "Female celebrity (resembling Liu Yifei)",
    "pose": "Front-facing, looking directly at the camera",
    "attire": {
      "outerwear": "Dark blue denim jacket with an open zipper, featuring decorative ruffles or fringes along the placket",
      "inner_wear": "White low-cut camisole or tank top"
    },
    "accessories": [
      "Large silver hoop earrings"
    ],
    "features": {
      "hair": "Long, straight black hair, slightly windswept",
      "makeup": "Natural yet defined eye makeup, nude lip color"
    },
    "background": "Solid light blue to white gradient background",
    "lighting": "Bright, soft studio lighting highlighting facial features"
  }
}
```

```json
{
  "image_description": {
    "subject": {
      "identity": "Female celebrity",
      "hair": "Long, straight black hair",
      "expression": "Serene gaze directly at the camera"
    },
    "outfit": {
      "top_outer": "Black blazer jacket draped over shoulders",
      "top_inner": "Black camisole/tank top with thin straps",
      "waist": "Black structured corset/bustier with buttons",
      "bottoms": "Dark blue denim jeans",
      "jewelry": [
        "Gold link chain necklace",
        "Small earrings"
      ]
    },
    "pose": {
      "arms": "Right arm raised with hand behind head; left hand placed in front pocket",
      "body": "Slight turn towards the camera"
    },
    "environment": {
      "background": "Soft, gradient light blue background (sky-like)"
    },
  }
}
```

```json
{
  "subject": {
    "description": "一位长发女性，身穿黑白搭配的时尚服装。"
  },
  "attire": {
    "top": "黑色丝绸质感的露肩上衣/衬衫，内搭白色抹胸",
    "bottom": "白色多层荷叶边短裙",
    "accessories": [
      "精致的项链"
    ]
  },
  "style": "时尚摄影, 商业广告",
  "color_palette": ["黑色", "白色", "灰色"]
}
```

```json
{
  "image_description": "这是一张时尚广告海报，展示了一个亚洲年轻女性作为内衣品牌代言人的形象。整体色调偏向冷艳和高级感，突出了“科技内衣”的主题。",
  "subject": {
    "role": "内衣全球品牌代言人",
    "appearance": {
      "hair": "黑色长直发，略显凌乱美，自然垂落在肩头",
      "makeup": "精致的淡妆，强调眼部轮廓，唇色自然偏红",
      "expression": "眼神清冷、自信，直视镜头"
    },
    "pose": "坐在一张复古风格的椅子上，身体微微侧倾，左手轻抬至脸颊旁，姿态放松而优雅"
  },
  "attire": {
    "inner_wear": "米白色吊带内衣，展现锁骨和肩部线条",
    "outer_wear": "一件黑色丝绸质感的宽松衬衫或睡袍，随意地披在肩上，呈现出一种慵懒的性感",
    "bottom": "下身穿着带有层叠蕾丝花边的白色短裙（仅露出部分裙摆）"
  },
  "accessories": [
    {
      "type": "项链",
      "description": "银色金属质感项链，设计简约独特，呈Y字形垂坠"
    },
    {
      "type": "耳环",
      "description": "细长的银色耳坠，点缀在耳边"
    }
  ],
  "background_and_setting": {
    "furniture": "一张带有法式古典风格的软包椅子，椅背上有淡雅的风景画图案",
    "environment": "室内摄影棚，背景较为模糊，光线柔和但对比度适中，营造出高级质感"
  },
}
```

```json
{
  "image_analysis": {
    "subject": "年轻女性",
    "attire": {
      "dress": "白色吊带短款连衣裙，V领设计，领口饰有蕾丝花边，裙摆为蓬松的多层荷叶边（类似芭蕾舞裙风格）",
      "legwear": "带有精致暗纹或印花的白色半透明连裤袜",
      "footwear": "裸色或浅粉色的尖头高跟鞋/芭蕾舞鞋"
    },
    "styling": {
      "hair": "深色长发，编成侧边的松散麻花辫，发间点缀有珍珠或亮片发饰",
      "accessories": "佩戴细项链、耳环以及手腕上的手链"
    },
    "pose": {
      "body_language": "身体微侧，倚靠在墙角的木质门框旁",
      "arms": "左手举起轻扶墙面，右手叉腰/轻触腰部",
      "expression": "神态自信优雅，直视镜头"
    },
    "background": {
      "setting": "室内环境，具有复古质感",
      "elements": [
        "米黄色带有纹理的墙面",
        "深棕色的木质踢脚线和门框",
        "右侧垂下的白色窗帘",
        "深色木地板"
      ]
    },
    "mood_style": "优雅、甜美、时尚、复古风"
  }
}
```


```json
{
   "image_description ":  "这是一张时尚广告照片，主要展示了一位身穿白色吊带连衣裙的女性模特。 ",
   "subject ": {
     "role ":  "内衣全球品牌代言人 ",
     "appearance ":  "深色长发编成侧边麻花辫，妆容精致，神情温柔自信。 ",
     "attire ": [
       "白色V领吊带连衣裙，带有蕾丝花边装饰 ",
       "白色蕾丝花纹连裤袜 ",
       "金色项链 ",
       "耳饰 "
    ],
     "pose ":  "坐在椅子上，身体微微前倾，一手轻抚裙摆，另一手自然垂放。 "
  },
   "visual_style ": {
     "lighting ":  "柔和的自然光 ",
     "color_palette ":  "以白色、米色为主，色调清新明亮 ",
     "mood ":  "优雅、舒适、高级感 "
  }
}
```


```json
{
   "image_description ":  "这是一张时尚广告海报，展示了一位年轻亚洲女性为内衣品牌拍摄的宣传照。 ",
   "subject ": {
     "role ":  "内衣全球品牌代言人 ",
     "appearance ":  "黑色长发编成侧边麻花辫，佩戴珍珠耳饰和项链，妆容精致清透。 "
  },
   "attire ": {
     "dress ":  "白色V领吊带连衣裙，领口有蕾丝装饰，裙摆呈多层蛋糕状蓬松设计。 ",
     "accessories ":  "手腕佩戴细手链，腿部穿着带有花纹的白色丝袜。 "
  },
   "pose ":  "身体微微侧向镜头，左手举起扶着旁边的木质门框，右手叉腰，眼神直视前方，姿态优雅自信。 ",
   "background ":  "背景为带有质感的米灰色墙面和深色的木质门框结构，光线柔和。 ",
}
```


```json
{
   "image_description ":  "一张全身时尚照片，展示了一位身着深蓝色晚礼服的女性优雅地侧躺在白色摄影棚地板上。 ",
   "visual_elements ": {
     "subject ":  "年轻女性，棕色长发，妆容精致，神情自信且略带慵懒。 ",
     "attire ": {
       "dress ":  "深蓝色丝绒质感的抹胸长裙，上半身饰有密集的深蓝色亮片或珠绣，呈现出类似扇贝或花瓣的纹理。裙摆处有高开叉设计，露出腿部。 ",
       "shoes ":  "宝蓝色细带高跟凉鞋，与礼服颜色相呼应。 ",
       "accessories ": [
         "一条细链项链，坠着一颗较大的浅蓝绿色水滴形宝石。 ",
         "同色系的方形耳钉。 "
      ]
    },
     "pose ":  "侧卧姿态。左手肘支撑地面，手掌托住脸颊；右手自然放置在腰臀部。双腿修长并交叉伸展，脚尖绷直。头部微微上扬，视线望向右侧上方。 ",
     "environment ":  "纯白色背景的摄影棚环境。左侧边缘可以看到黑色的摄影器材支架（如灯架或反光板架）的底部轮子。光线明亮均匀，突出了人物的轮廓和服装的质感。 "
  }
}
```

```json
{
   "image_description ": {
     "subject ":  "A young woman with long, wavy brown hair. ",
     "clothing ": {
       "dress ":  "A grey/silver satin strapless evening gown with a draped bodice and a high slit skirt that reveals her legs. ",
       "shoes ":  "Black strappy high-heeled sandals. "
    },
     "accessories ": [
       "A silver heart-shaped pendant necklace. ",
       "Long, dangling silver earrings. "
    ],
     "pose_and_expression ": {
       "posture ":  "She is sitting on a tall wooden stool with black metal legs. ",
       "arms ":  "Her arms are crossed confidently over her chest. ",
       "legs ":  "Her legs are crossed at the knee (one leg over the other). ",
       "expression ":  "She is looking directly at the camera with a calm, serious expression. "
    },
     "setting ": {
       "background ":  "Dark black curtains behind her and a white door frame to the left. "
    },
  }
}
```

```json
{
   "image_data ": {
     "description ":  "A close-up studio portrait of a woman with dark hair pulled back, wearing a sparkling silver high-neck top. ",
     "subject ": {
       "appearance ":  "Fair skin, defined winged eyeliner, neutral matte lipstick. ",
       "hair ":  "Dark black hair, styled in a sleek updo or bun, exposing the forehead and ears. ",
       "expression ":  "Serene, confident, looking directly at the camera. "
    },
     "attire ": {
       "garment ":  "Long-sleeved turtleneck or high-neck top. ",
       "material ":  "Sequined or heavily textured fabric that glitters/shimmers in silver/grey tones. ",
       "fit ":  "Fitted sleeves. "
    },
     "pose ": {
       "body_language ":  "Arms crossed over the chest. ",
       "angle ":  "Slightly angled body, face turned towards the lens. "
    },
     "setting ": {
       "background ":  "Soft, out-of-focus white or light grey background, possibly curtains. ",
       "lighting ":  "Bright, soft studio lighting that highlights facial features and the texture of the clothing. "
    },
     "tags ": [
       "portrait ",
       "fashion ",
       "glamorous ",
       "silver outfit ",
       "woman ",
       "studio photography "
    ]
  }
}
```

```json
{
   "image_data ": {
     "format ":  "jpeg ",
     "orientation ":  "portrait ",
     "description ":  "A vertical portrait of a woman posing against a white curtain background. ",
     "subject ": {
       "gender ":  "female ",
       "appearance ":  "Dark hair pulled back in a bun, fair skin, elegant makeup. ",
       "expression ":  "Calm, looking slightly to the side. "
    },
     "attire ": {
       "item ":  "Long-sleeved bodycon dress ",
       "color ":  "Silver/Light Lavender ",
       "texture ":  "Sequined, glittering, shiny ",
       "style ":  "High neck, tight-fitting "
    },
     "pose ":  "Arms raised behind the head, elbows out, showcasing the silhouette. ",
     "background ":  "White, vertical pleated curtains or drapes. ",
  }
}
```

```json
{
   "image_description ":  "A portrait of a young woman sitting indoors or on a balcony, holding a traditional round fan. ",
   "subject_details ": {
     "appearance ":  "Young female with fair skin, styled dark brown hair pulled back with loose strands framing the face, and light makeup featuring defined eyes and red lips. ",
     "pose ":  "Sitting, facing slightly to the right but looking directly at the camera. "
  },
   "attire_and_accessories ": {
     "clothing ":  "A white strapless dress or jumpsuit with a large pink floral pattern (resembling peonies) and green leaves. It features a twisted or gathered bodice detail. ",
     "jewelry ": [
       "A delicate gold necklace with a small pendant. ",
       "A gold chain bracelet on the left wrist. ",
       "A red string bracelet on the right wrist. "
    ],
     "props ":  "Holding a circular Chinese-style fan (tuan shan) with a painted floral design in her right hand. "
  },
   "background ": {
     "setting ":  "Looks like a window area or balcony. ",
     "elements ": [
       "A window with a black grid frame behind her. ",
       "Blue vertical blinds or curtains to the left. ",
       "Light-colored walls. "
    ]
  },
   "metadata ": {
     "style ":  "Portrait photography, soft lighting, aesthetic style common on social media platforms like Xiaohongshu or Zhihu. "
  }
}
```

```json
{
   "image_data ": {
     "description ":  "A young woman with long platinum blonde hair and bangs is shown from the knees up against a dark background. She is wearing a glamorous, gothic-style outfit featuring a sparkling silver or gold sequined bustier top and a voluminous black tulle skirt adorned with large, metallic rose appliqués. She wears a black choker and a long, elaborate necklace with a dark pendant. Her makeup includes defined eyes and red lips. She has rings on her fingers. ",
     "visual_elements ": {
       "hair_color ":  "Platinum Blonde ",
       "hairstyle ":  "Long straight with bangs ",
       "clothing_style ":  "High fashion / Stage costume ",
       "colors ": [ "Black ",  "Silver ",  "Gold ",  "Skin tone "],
       "lighting ":  "Spotlight on subject, dark background "
    },
  }
}
```

```json
{
   "image_url ":  "https://img.zhihu.com/pic/8f0b4a7d9e0f8c8d7b6a5e4f3c2b1a0d.jpg?imageView2/1/w/800/h/1000/format/webp/q/75 ",
   "description ":  "This image features a young woman with long, platinum blonde hair styled with bangs. She is wearing an elaborate outfit consisting of a sparkly, strapless corset-style top and a voluminous black tulle skirt adorned with large, sequined floral appliqués around the waist. Her accessories include a black choker, a long layered metal necklace with a pendant, gold earrings, and rings. The background is dark and out of focus, suggesting a stage or runway setting. There is a watermark in the bottom right corner that reads '知乎 @明星聊一聊'. "
}
```

```json
{
   "image_description ":  "一位年轻女性坐在汽车后座，身穿白色长袖衬衫和蓝色格纹百褶裙（JK制服风格）。她正拿着一台带有粉色珠链挂绳的银色数码相机看着屏幕，左手轻轻撩起头发。窗外可以看到模糊的桥梁栏杆。 ",
   "details ": {
     "subject ":  "年轻女性 ",
     "attire ": [
       "白色长袖衬衫 ",
       "深蓝色格纹领结 ",
       "深蓝色格纹百褶裙 ",
       "黑色过膝袜 "
    ],
     "accessories ": [
       "银色数码相机 ",
       "粉色串珠相机带 ",
       "美甲 "
    ],
     "action ":  "手持相机查看/自拍，手扶头发 ",
     "location ":  "汽车后座 ",
     "background ":  "车窗外的桥梁结构，天气看起来较为阴沉 "
  },
}
```

```json
{
   "image_data ": {
     "subject ":  "A woman posing for a portrait ",
     "appearance ": {
       "hair ":  "Dark brown hair styled with bangs and tied back, possibly in low pigtails ",
       "accessories ":  "Two bright red bows or hair clips placed on either side of her head ",
       "makeup ":  "Natural look with defined eyes and soft pink lips ",
       "expression ":  "Gentle smile, looking directly at the camera "
    },
     "clothing ": {
       "garment ":  "A vibrant red dress ",
       "style ":  "Off-the-shoulder (strapless) design with loose, fluttery sleeves hanging off the arms ",
       "fit ":  "Fitted bodice accentuating the figure "
    },
     "setting ": {
       "background ":  "A dark, textured wall or paneling, possibly wood or stone ",
       "lighting ":  "Indoor lighting that casts a shadow behind her to the left, highlighting her face and shoulders "
    }
  }
}
```

```json
{
   "image_url ":  "https://i.imgur.com/example_image_id.jpg ", 
   "description ":  "A split-screen fashion photograph featuring a woman in two different poses and outfits. ",
   "panels ": [
    {
       "side ":  "left ",
       "outfit ": {
         "color ":  "Deep Navy Blue ",
         "material ":  "Velvet with sequin embellishments ",
         "style ":  "Strapless bodycon dress with a plunging neckline and a high thigh slit ",
         "shoes ":  "Blue strappy high heels "
      },
       "pose ":  "Leaning against a white wall, one arm raised behind her head, looking down and to the side. ",
       "accessories ": [
         "Silver necklace with a blue pendant ",
         "Matching earrings "
      ]
    },
    {
       "side ":  "right ",
       "outfit ": {
         "color ":  "Greyish-Purple / Taupe ",
         "material ":  "Satin or Silk ",
         "style ":  "Draped strapless gown with a high leg slit ",
         "shoes ":  "Black strappy high heels "
      },
       "pose ":  "Sitting on a tall stool, legs crossed, arms folded across chest, looking directly at the camera. ",
       "accessories ": [
         "Thin silver necklace ",
         "Sparkling drop earrings "
      ]
    }
  ],
}
```

```json
{
   "image_info ": {
     "description ":  "一位年轻女性在室内对着镜子自拍。 ",
     "subject ": {
       "gender ":  "female ",
       "hair ":  "black, shoulder-length, slightly messy style with bangs ",
       "pose ":  "holding a phone up to a mirror, obscuring part of her face "
    },
     "attire ": {
       "top ":  "grey sleeveless camisole/tank top with lace trim around the neckline ",
       "bottom ":  "dark blue denim jeans "
    },
     "objects ": {
       "phone_case ": {
         "color ":  "orange/translucent ",
         "pattern ":  "cartoon yellow ducks (possibly Donald Duck related) "
      }
    },
     "background ": {
       "setting ":  "bedroom or hotel room ",
       "elements ": [
         "large mirror reflecting the room ",
         "bed with white linens ",
         "wooden flooring ",
         "wall lamp "
      ]
    },
  }
}
```

```json
{
   "image_data ": {
     "description ":  "一张人像摄影照片，画面中一位年轻女性坐在床上。她有着深色微卷的长发，妆容精致，脸颊带有明显的粉色腮红。她身穿一套粉色的丝绸质感的睡衣（吊带裙外搭开衫），姿态慵懒优雅。她的双手轻轻握着一支盛开的白粉色百合花，目光温柔地望向侧上方。在她的腿边放着一本打开的书。整体光线柔和温暖，呈现出一种唯美、梦幻的氛围。 ",
     "elements ": [
      {
         "type ":  "person ",
         "details ":  "年轻女性，长卷发，粉色妆容 "
      },
      {
         "type ":  "clothing ",
         "details ":  "粉色丝绸吊带裙，同色系丝绸外套 "
      },
      {
         "type ":  "object ",
         "details ":  "一支白粉相间的百合花 "
      },
      {
         "type ":  "object ",
         "details ":  "一本摊开的书 "
      },
      {
         "type ":  "lighting ",
         "details ":  "自然光，暖色调，逆光感 "
      }
    ],
     "style ":  "唯美，日系写真，柔焦 "
  }
}
```

```json
{
   "image_metadata ": {
     "format ":  "JPEG ",
     "orientation ":  "Portrait ",
     "style ":  "Photorealistic, Portrait Photography "
  },
   "description ": {
     "subject ":  "A young woman with fair skin and dark hair styled in a loose low bun with wispy bangs. ",
     "attire ":  "Wearing a tight-fitting, beige or nude-colored spaghetti strap dress. ",
     "pose ":  "Standing sideways, leaning her left shoulder against a large, reddish-brown wooden pillar. Her head is turned slightly to the right, looking off into the distance. ",
     "lighting ":  "Natural sunlight hitting from the right side, creating highlights on her face, shoulder, and chest, casting soft shadows. ",
     "background ":  "Blurred background suggesting a traditional Chinese architectural setting, possibly a pavilion or courtyard, with hints of grey roofing tiles. "
  },
   "tags ": [
     "beauty ",
     "portrait ",
     "woman ",
     "summer dress ",
     "sunlight ",
     "traditional architecture ",
     "elegant ",
     "serene "
  ]
}
```

```json
{
   "image_analysis ": {
     "subject ": {
       "gender ":  "female ",
       "age_range ":  "young_adult ",
       "expression ":  "gentle, looking directly at camera ",
       "pose ":  "holding a pearl necklace horizontally across her eyes "
    },
     "appearance ": {
       "hair ": {
         "color ":  "dark brown ",
         "style ":  "updo with loose strands ",
         "accessories ": [
           "small white flowers (baby's breath) on both sides "
        ]
      },
       "makeup ": {
         "eyes ":  "natural, defined lashes ",
         "lips ":  "glossy coral/orange tint "
      }
    },
     "attire ": {
       "type ":  "lingerie or sleepwear ",
       "color ":  "cream/white ",
       "details ": [
         "lace trim ",
         "spaghetti straps ",
         "buttons down the front "
      ]
    },
     "props ": {
       "item ":  "pearl necklace ",
       "position ":  "held by both hands in front of the eyes "
    },
     "environment_and_lighting ": {
       "lighting ":  "soft natural sunlight, creating highlights on skin and hair ",
       "background ":  "blurred, indoor setting, warm tones ",
       "mood ":  "dreamy, romantic, soft, ethereal "
    },
     "metadata ": {
       "orientation ":  "portrait "
    }
  }
}
```

```json
{
   "image_content ": {
     "main_subject ": {
       "type ":  "human ",
       "gender ":  "female ",
       "hair_color ":  "black ",
       "expression ":  "smiling ",
       "action ":  "squatting "
    },
     "attire ": {
       "top ":  "loose green knit sweater/cardigan (off-the-shoulder style) ",
       "bottom ":  "denim shorts ",
       "footwear ":  "brown flat sandals "
    },
     "secondary_subject ": {
       "type ":  "animal ",
       "species ":  "cat ",
       "color ":  "orange tabby ",
       "position ":  "standing on a table in the background "
    },
     "setting ": {
       "location ":  "outdoor street or courtyard ",
       "background_elements ": [
         "wooden table covered with a pink patterned cloth ",
         "buildings with awnings ",
         "blurred background "
      ]
    },
     "photography_style ": {
       "lighting ":  "natural daylight ",
       "focus ":  "shallow depth of field (bokeh background) "
    }
  }
}
```

```json
{
   "image_description ": {
     "subject ":  "A young woman kneeling on a wooden floor ",
     "pose ":  "Arms raised high in a stretching motion, eyes closed, head tilted slightly back ",
     "attire ": {
       "top ":  "Dark blue ribbed long-sleeve crop cardigan with buttons ",
       "bottom ":  "Grey plaid pleated mini skirt (school uniform style) ",
       "hosiery ":  "Black opaque tights or pantyhose ",
       "accessories ":  "Round wire-rimmed glasses "
    },
     "hair ":  "Dark hair tied up in a bun ",
     "expression ":  "Relaxed, serene, enjoying the stretch ",
     "background ": {
       "setting ":  "Indoor living room ",
       "lighting ":  "Bright natural light coming from a window on the left ",
       "furniture ":  "Brown leather sofa visible on the right side ",
       "floor ":  "Light wood flooring "
    },
     "style ":  "Realistic photography style, likely AI-generated given the lighting and texture ",
  }
}
```

```json
{
   "image_data ": {
     "subject ":  "Asian woman ",
     "action ":  "Lying on a sofa ",
     "attire ": {
       "garment ":  "Dress ",
       "color ":  "Beige/Light Pink ",
       "pattern ":  "Polka dots ",
       "style ":  "Spaghetti strap, Slip dress "
    },
     "accessories ": [
       "Glasses ",
       "Black frames "
    ],
     "setting ": {
       "location ":  "Indoors ",
       "furniture ":  "Gray sofa ",
       "background ":  "Window with natural light "
    },
     "visual_style ":  "Portrait photography, soft lighting "
  }
}
```

```json
{
   "image_analysis ": {
     "subject ":  "年轻女性 ",
     "appearance ": {
       "hair ":  "深色头发向后梳理并盘起，额前留有轻薄的空气刘海和几缕自然的碎发垂在脸颊两侧。 ",
       "accessories ": [
         "右侧头发上别着一个细长的、镶满水钻或珍珠的发夹。 ",
         "左耳佩戴着一颗小巧精致的耳钉。 "
      ],
       "makeup ":  "妆容精致清透，眼妆强调了卷翘的睫毛和棕色系眼影，嘴唇涂有光泽感强的橘红色/珊瑚色唇釉。 "
    },
     "clothing ":  "身穿一件白色衬衫，领口开得较宽，露出锁骨和颈部线条，衣物质感看起来柔软舒适。 ",
     "pose_and_expression ": {
       "pose ":  "呈侧卧或趴着的姿态，右手手背轻托着右侧脸颊，手指自然弯曲。 ",
       "expression ":  "头部微微倾斜，双眼直视镜头，眼神柔和、清澈，表情显得慵懒而迷人。 "
    },
     "setting_and_lighting ": {
       "background ":  "背景模糊，呈现出米白色或浅灰色的色调，看起来像是在沙发或床上拍摄的室内场景。 ",
       "lighting ":  "光线柔和且均匀，营造出温暖、明亮的氛围，具有典型的日系或韩系写真的质感。 "
    },
     "style_mood ":  "整体风格唯美、清新，带有一种邻家女孩的甜美感和轻微的性感气息。 "
  }
}
```

```json
{
   "image_analysis ": {
     "subject ":  "Young woman ",
     "appearance ": {
       "hair ":  "Short, straight black hair (bob cut) ",
       "expression ":  "Smiling gently, looking over her shoulder towards the camera ",
       "complexion ":  "Fair skin "
    },
     "clothing ": {
       "inner_layer ":  "White sleeveless camisole or tank top with a low neckline ",
       "outer_layer ":  "Pink striped button-down shirt, worn loosely draped off the shoulders ",
       "accessories ":  "A thin white choker necklace "
    },
     "setting ": {
       "location ":  "Staircase / Stairwell ",
       "background_details ": [
         "Peeling white walls ",
         "Exposed electrical wires running along the wall ",
         "Metal handrails ",
         "A closed metal shutter door in the background "
      ],
       "atmosphere ":  "Old, slightly gritty, urban decay aesthetic "
    },
     "photography_style ": {
       "lighting ":  "Natural but somewhat dim, creating soft shadows ",
       "tone ":  "Vintage, film-grain effect, candid portrait style "
    }
  }
}
```

```json
{
   "image_analysis ": {
     "subject ": {
       "gender ":  "female ",
       "hair ":  "short black bob cut ",
       "expression ":  "smiling, looking at camera ",
       "pose ":  "standing, slightly turned to the side, looking back over shoulder "
    },
     "attire ": {
       "inner_layer ":  "white low-cut tank top/camisole ",
       "outer_layer ":  "loose pink button-down shirt (worn open/off-shoulder) ",
       "accessories ":  "thin white necklace/choker "
    },
     "setting ": {
       "location ":  "looks like a cluttered storage area, basement, or old alleyway ",
       "left_side ":  "weathered concrete wall with messy hanging wires and cables ",
       "right_side ":  "shelves or piles of cardboard boxes and miscellaneous items ",
       "background ":  "dark, possibly a shuttered door or window with horizontal slats "
    },
     "photography_style ": {
       "lighting ":  "harsh flash lighting (typical of film photography), creating high contrast between the bright subject and dark background ",
       "mood ":  "grunge, vintage, Y2K aesthetic, candid ",
       "color_palette ":  "dark tones in background, bright skin tone, white and pink clothing "
    }
  }
}
```

```json
{
   "image_data ": {
     "description ":  "A photo of a young woman posing in what appears to be a cluttered storage area or back alley. ",
     "subject ": {
       "gender ":  "female ",
       "hair ":  "short, straight black hair ",
       "expression ":  "smiling slightly, looking back over shoulder ",
       "attire ": [
         "white spaghetti strap tank top ",
         "pink shirt or jacket draped loosely over one shoulder ",
         "black bottoms (partially visible) "
      ]
    },
     "environment ": {
       "location_type ":  "storage room / basement / utility area ",
       "background_elements ": [
         "metal shelving unit filled with cardboard boxes and miscellaneous items ",
         "closed metal roll-up shutter door ",
         "exposed electrical wiring and cables near the ceiling ",
         "fluorescent tube lighting ",
         "rough concrete walls "
      ],
       "lighting ":  "dim, artificial overhead light creating some shadows "
    },
     "style ": {
       "tone ":  "candid, casual ",
       "aesthetic ":  "gritty, urban, lo-fi "
    }
  }
}
```

```json
{
   "image_analysis ": {
     "subject ":  "A young woman posing for a photo ",
     "appearance ": {
       "hair ":  "Dark hair styled in an updo with loose strands framing the face ",
       "makeup ":  "Glamorous makeup with defined eyes and reddish-orange lipstick ",
       "expression ":  "Calm, looking directly at the camera "
    },
     "outfit ": {
       "type ":  "Evening gown / Cocktail dress ",
       "color ":  "Black ",
       "details ": [
         "Strapless design ",
         "Bodice features a textured, possibly sequined or beaded butterfly/moth wing motif ",
         "Skirt appears to have a tinsel or metallic fringe texture that sparkles ",
         "Wearing a sheer black glove on her left arm "
      ]
    },
     "accessories ": [
       "A diamond or crystal choker necklace ",
       "Matching earrings "
    ],
     "background ": {
       "elements ": [
         "Gold-colored horizontal railings or pipes ",
         "Blurred background suggesting an indoor event or venue ",
         "Bright light source on the right side "
      ]
    },
  }
}
```

```json
{
   "image_description ":  "A romantic and intimate portrait of a young couple in an indoor setting. ",
   "subjects ": [
    {
       "gender ":  "Male ",
       "appearance ":  "Short black hair, fair skin. ",
       "attire ":  "White long-sleeved dress shirt, loose black tie, black trousers. ",
       "pose ":  "Kneeling or sitting lower than the female, looking up at her face. ",
       "interaction ":  "The female is gently touching his lips/chin with her fingers. "
    },
    {
       "gender ":  "Female ",
       "appearance ":  "Long, dark, wavy hair cascading over one shoulder. ",
       "attire ":  "Light pink or champagne-colored sheer slip dress with ruffled layers. ",
       "accessories ":  "Silver necklace with a pendant, drop earrings, butterfly-shaped bracelet. ",
       "pose ":  "Sitting on a bed or sofa, leaning slightly forward. ",
       "expression ":  "Looking down at the male with a soft expression. "
    }
  ],
   "setting ": {
     "location ":  "Indoors, likely a bedroom or studio. ",
     "background_elements ": [
       "Dark wood paneled walls. ",
       "Two framed pictures of butterfly specimens hanging on the wall behind them. ",
       "A bed or sofa covered with light-colored, textured fabric (linen or sheet). "
    ]
  },
   "mood_lighting ": {
     "lighting ":  "Soft, warm, diffused lighting creating gentle shadows. ",
     "atmosphere ":  "Romantic, elegant, cinematic, quiet intimacy. "
  },
}
```

```json
{
   "image_description ":  "A romantic and intimate portrait of a young couple in an indoor setting. ",
   "subjects ": [
    {
       "gender ":  "Male ",
       "appearance ":  "Short black hair, fair skin. ",
       "attire ":  "White long-sleeved dress shirt, loose black tie, black trousers. ",
       "pose ":  "Kneeling or sitting lower than the female, looking up at her face. ",
       "interaction ":  "The female is gently touching his lips/chin with her fingers. "
    },
    {
       "gender ":  "Female ",
       "appearance ":  "Long, dark, wavy hair cascading over one shoulder. ",
       "attire ":  "Light pink or champagne-colored sheer slip dress with ruffled layers. ",
       "accessories ":  "Silver necklace with a pendant, drop earrings, butterfly-shaped bracelet. ",
       "pose ":  "Sitting on a bed or sofa, leaning slightly forward. ",
       "expression ":  "Looking down at the male with a soft expression. "
    }
  ],
   "setting ": {
     "location ":  "Indoors, likely a bedroom or studio. ",
     "background_elements ": [
       "Dark wood paneled walls. ",
       "Two framed pictures of butterfly specimens hanging on the wall behind them. ",
       "A bed or sofa covered with light-colored, textured fabric (linen or sheet). "
    ]
  },
   "mood_lighting ": {
     "lighting ":  "Soft, warm, diffused lighting creating gentle shadows. ",
     "atmosphere ":  "Romantic, elegant, cinematic, quiet intimacy. "
  },
}
```

```json
{
   "image_description ": {
     "subject ": {
       "gender ":  "female ",
       "hair ":  "long, dark, wavy hair ",
       "facial_expression ":  "calm, looking slightly to the side, soft makeup "
    },
     "attire ": {
       "type ":  "modified cheongsam / qipao dress ",
       "color ":  "pale yellow / cream ",
       "material ":  "satin-like sheen with lace details ",
       "features ": [
         "high collar ",
         "deep V-neckline with lace trim ",
         "sheer lace panel on the upper chest ",
         "ruffled short sleeves ",
         "form-fitting silhouette "
      ]
    },
     "accessories ": {
       "earrings ":  "long, dangling silver or crystal earrings "
    },
     "pose_and_action ": {
       "position ":  "sitting ",
       "body_angle ":  "side profile, leaning slightly forward ",
       "hand_position ":  "one hand resting on the surface behind her for support "
    },
     "setting ": {
       "background ":  "plain, textured beige or light brown wall ",
       "surface ":  "marble or stone ledge/bench "
    },
     "metadata ": {
       "lighting ":  "soft, warm indoor lighting "
    }
  }
}
```

```json
{
   "image_description ":  "A photo taken in a dimly lit room, likely at a party or club. ",
   "subjects ": [
    {
       "type ":  "person ",
       "gender ":  "female ",
       "position ":  "foreground_center ",
       "appearance ": {
         "hair ":  "dark, pulled back with a white ribbon or bow accessory ",
         "skin_tone ":  "fair ",
         "makeup ":  "natural look with red lips "
      },
       "clothing ": {
         "item ":  "dress ",
         "color ":  "light beige or champagne silk/satin material ",
         "style ":  "form-fitting, cut-out design at the chest, thin straps "
      },
       "action ":  "holding the straps of her dress near her shoulders with both hands ",
       "lighting_effect ":  "warm yellow light projected onto her skin and dress, creating dappled shadows "
    },
    {
       "type ":  "person ",
       "gender ":  "male ",
       "position ":  "background_left ",
       "visibility ":  "silhouetted/obscured ",
       "clothing ":  "dark shirt "
    }
  ],
   "environment ": {
     "setting ":  "indoor ",
     "lighting ":  "low light, dramatic contrast ",
     "background_elements ": [
      {
         "element ":  "projection screen or window ",
         "location ":  "left ",
         "visual ":  "blue patterned light projection (resembling water ripples or leaves) "
      },
      {
         "element ":  "curtains ",
         "location ":  "right ",
         "color ":  "dark grey or black "
      }
    ]
  },
   "mood ":  "moody, atmospheric, intimate "
}
```

```json
{
   "image_description ": {
     "subject ":  "A woman standing in a grassy field ",
     "appearance ": {
       "hair ":  "Long, brownish-red hair styled in a loose side braid ",
       "expression ":  "Smiling gently, looking slightly upwards and to the left ",
       "attire ":  "A dark brown or black lace spaghetti-strap dress with intricate texture ",
       "accessories ":  "Large gold earrings "
    },
     "action ":  "Holding a few stems of blue wildflowers in her hands ",
     "setting ": {
       "environment ":  "An outdoor meadow or field ",
       "foreground ":  "Tall green grass and scattered blue wildflowers (possibly cornflowers) ",
       "background ":  "A blurred landscape, possibly hills or water under a soft sky "
    },
     "lighting ":  "Natural sunlight, creating a warm and soft atmosphere ",
     "metadata ": {
    }
  }
}
```

```json
{
  "description ":  "这是一张充满田园诗意与宁静氛围的人像摄影。照片中，一位年轻女子身穿深褐色的蕾丝吊带长裙，站在一片开满蓝色野花的绿色草地中。她梳着侧边的麻花辫，佩戴着金色的耳饰，脸上带着温柔恬静的微笑，目光望向左侧的远方。她的双手轻轻握着几株细长的野草和蓝色小花。背景是柔和的自然光，远处似乎是平静的水面或河岸，整体色调温暖而唯美。 "
  }
```

```json
 {
     "description ":  "This is a portrait photograph filled with pastoral poetry and a serene atmosphere. In the photo, a young woman wearing a dark brown lace slip dress stands amidst a green meadow blooming with blue wildflowers. She has her hair styled in a side braid, wears gold earrings, and sports a gentle, tranquil smile as she gazes towards the distance on her left. Her hands are gently holding a few stalks of grass and small blue flowers. The background features soft natural light, suggesting a calm body of water or riverbank in the distance, creating an overall warm and aesthetic tone. "
  }
```

```json
{
   "image_analysis ": {
     "subject ": {
       "gender ":  "female ",
       "hair ": {
         "color ":  "black ",
         "style ":  "long side braid ",
         "details ":  "loose strands framing the face "
      },
       "pose ":  "sitting sideways, looking to the right, left hand touching the braid ",
       "expression ":  "calm, elegant, slightly pensive "
    },
     "attire ": {
       "type ":  "off-shoulder evening gown ",
       "color ":  "champagne or light beige ",
       "texture ":  "embellished with sequins, beads, or lace patterns ",
       "sleeves ":  "sheer, puffy, textured fabric covering the upper arms "
    },
     "accessories ": [
      {
         "item ":  "earrings ",
         "description ":  "large, white, teardrop-shaped dangling earrings "
      }
    ],
     "setting ": {
       "lighting ":  "soft, warm, low-key lighting creating a cinematic mood ",
       "background ":  "dark and indistinct, possibly an indoor setting with wooden elements ",
       "foreground_elements ":  "a white vertical structure (possibly a door frame or wall edge) on the right side "
    },
     "metadata ": {
       "estimated_source ":  "Social media post (Zhihu) "
    }
  }
}
```

```json
{
   "一张高画质的人像摄影，一位年轻的亚洲女性，拥有白皙的皮肤和精致的五官。她留着黑色的长发，编成一条松散的侧边麻花辫，垂落在左肩前。她身穿一件优雅的米白色露肩礼服，礼服上半部分有精美的蕾丝和珠绣装饰，显得非常华丽。她佩戴着夸张的银色水滴形耳环和戒指。她的姿态优雅，身体微微侧转，目光望向右侧，神情略带清冷和沉思。她的手指轻轻搭在辫子上。背景较暗，右侧有一个模糊的白色柱状结构，营造出一种室内高级晚宴或杂志拍摄的氛围。光线柔和，带有一点复古胶片的颗粒感和电影质感。 ",
}
```

```json
{
    "A high-quality portrait photography of a young Asian woman with fair skin and delicate features. She has long black hair styled in a loose side braid that drapes over her left shoulder. She is wearing an elegant off-the-shoulder beige gown, featuring exquisite lace and beadwork embroidery on the bodice, looking very luxurious. She wears statement silver teardrop earrings and rings. Her pose is graceful, body turned slightly, gazing to the right with a cool and contemplative expression. Her fingers are gently touching her braid. The background is dark, with a blurred white column-like structure on the right, creating an atmosphere of an upscale indoor event or magazine shoot. The lighting is soft, with a touch of vintage film grain and a cinematic texture. "
}
```




```json
  {
    "一位年轻亚洲女性坐在汽车后座，面带微笑看向镜头，右手举起轻轻挥手致意，左手拿着手机。她留着深色长发，身穿浅棕色无袖上衣，手腕佩戴白色智能手表。车座为深灰色皮质，带有红色缝线装饰，头枕处有黑色颈枕。车窗外可见模糊的绿色植被和护栏，光线明亮柔和，整体氛围轻松自然、生活化。拍摄角度为车内近景，构图聚焦人物表情与动作，背景虚化突出主体。",
    }
```

```json
  {"一位年轻亚洲女性在夜晚户外微笑，她留着柔顺的深棕色长发，身穿一件带有灰绿色植物印花的半透明雪纺衬衫，搭配黑色下装。背景是虚化的夜景，有被灯光照亮的绿树和模糊的街灯，营造出温暖柔和的氛围。她坐在一张深色金属框架的户外椅子上，身体微微侧转，目光温柔直视镜头，笑容自然甜美。画面采用浅景深，突出人物主体，光线来自左上方，柔和地打在她的脸上，整体色调偏暖，充满宁静与生活气息。
}
```

```json
A young Asian woman smiling warmly at night outdoors, long smooth dark brown hair, wearing a semi-transparent chiffon blouse with gray-green botanical print and black bottom. She is seated on a dark metal-framed outdoor chair, body slightly turned, gazing gently into the camera with a natural, sweet smile. Background features softly blurred night scenery with illuminated green trees and distant streetlights, creating a cozy and gentle ambiance. Shallow depth of field emphasizes the subject, soft lighting from upper left illuminates her face, warm color tone overall, serene and full of everyday life charm.
```

```json
一位年轻亚洲女性坐在室内柜台旁，身穿米白色长款风衣，内搭深蓝色连衣裙与领结，留着齐肩棕色直发，面带温柔微笑注视镜头。她身旁放置一个透明亚克力礼盒，内装粉色玫瑰花制成的独角兽造型花艺，独角兽头戴银色角与白色鬃毛，礼盒系有印“BEST WISHES FOR YOU”字样的粉色丝带。背景为浅灰色纹理墙面，右侧可见电源插座，地面为灰白斑点水磨石台面。整体光线柔和，氛围温馨浪漫，构图偏右侧人物主体，左侧留出花艺展示空间，风格写实自然，适合用于社交媒体或礼物场景。
```

```json
 A young Asian woman sitting on a speckled white-and-gray countertop indoors, wearing a long off-white trench coat over a navy blue dress with a matching bow tie. She has shoulder-length straight brown hair and is smiling gently at the camera. Next to her is a transparent acrylic gift box containing a pink rose unicorn sculpture — the unicorn has a silver horn, fluffy white mane, and is wrapped with a pink ribbon that reads “BEST WISHES FOR YOU.” The background features a light gray textured wall with a visible power outlet on the right. Soft ambient lighting creates a warm, romantic atmosphere. Realistic photography style, composition focused on the woman slightly right of center, leaving space for the unicorn gift on the left. Ideal for social media or gifting context.
```

```json
一位年轻亚洲女性，留着齐刘海及肩黑发，部分头发在脑后挽成优雅低发髻，几缕卷发垂落颈侧。她身穿一件米白色单肩礼服，肩部有轻盈飘逸的薄纱披肩，胸前饰有精致金属花朵胸针，礼服上隐约可见刺绣花纹。她坐在一张浅灰色皮质沙发中，背景是带有纹理的米白色墙面，光线柔和自然，营造出温馨高雅的氛围。人物表情温柔平静，直视镜头，妆容淡雅，佩戴小巧珍珠耳钉。整体构图为中近景人像，突出人物气质与服装细节，风格写实、清新、略带复古感。
```

```json   
A young Asian woman with straight black shoulder-length hair and bangs, one side elegantly pinned back into a low bun with soft curls framing her neck. She wears an off-shoulder cream-colored gown with a flowing sheer drape over one arm, adorned with a delicate metallic floral brooch at the bust and subtle embroidered patterns on the bodice. Seated on a light gray leather sofa against a textured off-white wall, she gazes softly at the camera with gentle expression, wearing minimal makeup and small pearl stud earrings. Soft natural lighting enhances the serene, elegant, slightly vintage atmosphere. Medium close-up portrait, photorealistic, high detail, clean composition, warm and sophisticated mood.
```

```json
一位年轻女性的特写自拍，她戴着黑色细框圆形眼镜，黑色中长发自然垂落，身穿黑色V领上衣，微微仰头看向镜头，嘴唇微张，表情自然放松。背景为深色软垫或沙发，光线柔和偏暖，突出面部轮廓与皮肤质感，整体氛围安静、日常、有生活感。高清晰度，细节丰富，真实摄影风格。
```

```json
一位年轻优雅的亚洲女性走在城市商业街的人行道上，身穿修身黑色吊带鱼尾长裙，肩带纤细，领口方正，裙摆随步伐轻扬。她留着自然微卷的深棕色中长发，面带温柔微笑直视镜头，颈间佩戴一条精致细链项链。右手提着一只米白色几何造型手提包，脚穿裸色高跟鞋（部分可见）。背景是现代都市街景：左侧有黑色花箱种植橙红色花卉，后方是玻璃幕墙建筑，墙上挂有男性时尚广告海报；右侧远处可见一名穿白衬衫黑裤的保安站立在商场入口。阳光从左上方斜照，地面铺有灰色地砖，光影分明，整体氛围时尚、清新、高级感十足，构图采用中景人像，焦点清晰，背景虚化，呈现电影感胶片色调。
```

```json
一位年轻女性跪坐在床上，身穿一件浅粉色高开叉挂脖连衣裙，搭配白色过膝长袜。她留着金色齐刘海与深色马尾辫，妆容精致，眼神直视镜头。左手轻抚身后一幅梦幻风景挂画——画中是粉紫色云朵、新月和远山。背景左侧可见蓝色小柜子和卡通图案布帘。整体光线柔和，色调温馨浪漫，营造出甜美又略带性感的卧室氛围。画面构图居中，人物姿态优雅舒展，细节清晰，质感细腻。
```

```json
一位年轻女性坐在木地板上，双腿张开，身穿白色短袖水手服衬衫，领口系着红色蝴蝶结，衬衫敞开露出白色内衣，下身穿着蓝红格纹百褶短裙，搭配白色过膝长袜。她低头看向地面，面部被模糊处理。背景是明亮的窗户，阳光透过薄纱窗帘洒入室内，在地板上形成柔和光斑与条纹阴影。画面整体色调偏暖，带有柔焦与轻微过曝效果，营造出朦胧、静谧的日系氛围。右下角可见部分黄色布料物体。画面中央有半透明水印文字“bunnylin-love.tumblr.com”。镜头采用低角度平视拍摄，构图居中，强调光影与人物姿态。
```

```json
A young woman sitting on a polished wooden floor with legs spread apart, wearing a white short-sleeved sailor-style shirt with an open front revealing a white bralette, tied with a red ribbon bow at the collar, paired with a pleated plaid skirt in blue and red tones, and white knee-high socks. She is looking down with her face blurred. Behind her, bright sunlight streams through sheer white curtains from a large window, casting soft highlights and striped shadows across the floor. The scene has a warm, hazy, overexposed aesthetic with soft focus, evoking a quiet, dreamy Japanese-style atmosphere. A yellow fabric object is partially visible in the lower right corner. Centered composition, low-angle eye-level shot. Semi-transparent watermark text “bunnylin-love.tumblr.com” centered on image. Style: photorealistic, soft lighting, cinematic mood, gentle color grading.
```
 
```json
一位年轻女性，闭着眼睛，表情放松，穿着粉色透明女仆装，领口有白色蝴蝶结装饰，搭配白色蕾丝边吊带袜。她留着黑色长发，扎成双马尾，头戴白色蕾丝发饰。坐在柔软的白色毛绒地毯上，背景是室内环境，光线柔和明亮，整体氛围甜美、梦幻、性感。风格为高清写实日系少女风，细节精致，皮肤光滑，光影自然。
```

```json
一位拥有银白色长发和蓝色大眼睛的年轻女性，正坐在柔软的白色地毯上。她穿着一件白色短袖连体衣，衣上有青绿色图案和粉色花朵装饰，袖口与裤脚边缘有青绿色条纹。她的头发两侧各别着一个粉色蝴蝶结发饰，双手轻轻拉开胸前的衣襟，露出部分肌肤，表情略带羞涩地直视镜头。背景为浅米色墙面，右侧可见藤编家具一角，左侧有镜子反光，整体光线柔和明亮，营造出温馨可爱的室内氛围。风格为高精度写实cosplay摄影，细节清晰，色彩柔和，适合用于Z-image生成。
```

```json
一位年轻女性跪坐在白色床上，身穿白色蕾丝边女仆装，搭配黑色丝袜和同款蕾丝吊袜带。她留着深棕色双马尾长发，齐刘海，妆容精致，红唇微启，眼神直视镜头，表情温柔略带羞涩。背景为明亮简约的室内空间，白色墙壁、拱形门洞、远处可见摄影灯架与置物柜，床边放有米色抱枕。整体光线柔和自然，色调清新干净，画面聚焦人物，构图居中，氛围甜美私密。
```    

```json 
a young beautiful woman kneeling on a white bed, wearing a white frilly maid outfit with black trim, black thigh-high stockings with lace garters, long dark brown hair in twin ponytails with bangs, soft makeup and red lips, looking directly at the camera with gentle shy expression, bright minimalist room background with white walls, arched doorway, photography light stand and storage cabinet visible in distance, beige pillow beside her, soft natural lighting, clean pastel tones, centered composition, sweet and intimate atmosphere, high detail, realistic skin texture, 8K ultra HD
```

```json
一位年轻女性坐在铺着白色床单的床上，她有着一半白一半黑的长直发，头顶戴着一对黑色毛绒熊猫耳朵发饰。她身穿一件半透明的白色旗袍式连体衣，领口和侧边有黑色镶边，胸前是黑色系带设计，内搭黑色心形金属环装饰的胸衣。她穿着黑色过膝丝袜，双腿微张跪坐，双手自然放在膝盖附近，面带微笑直视镜头。背景是明亮的现代卧室，左侧墙上挂着投影幕布，远处可见白色吧台椅和拱形门廊，床边散落着零食包装和一个米色抱枕。整体光线柔和自然，色调干净清新，营造出甜美又略带性感的氛围。
```    
   
```json
A young woman with half-white, half-black long straight hair and black fluffy panda ear headband, sitting on a white bed in a bright modern bedroom. She wears a semi-transparent white cheongsam-style bodysuit with black trim and lace-up front, revealing a black bra with heart-shaped metal ring detail. She’s wearing black thigh-high stockings, kneeling with legs slightly apart, hands resting gently on her knees, smiling softly at the camera. Background includes a projector screen on the left wall, white bar stools and arched doorway in the distance, scattered snacks and a beige pillow beside her. Soft natural lighting, clean aesthetic, sweet yet subtly sensual vibe. High detail, photorealistic, 8K resolution, full-body portrait, centered composition.
```

```json
一位年轻女性坐在床上，身穿白色针织羊角主题服装，头戴带有米色螺旋羊角的白色毛绒发箍，黑色长发扎成双马尾，穿着白色高领镂空针织上衣（胸前有系带设计），搭配白色透明丝袜和白色针织蝴蝶结装饰的过膝袜套。她双腿交叠，手轻抚衣襟，眼神直视镜头，表情温柔略带羞涩。背景是温馨卧室，左侧有木质置物架，右侧是浅棕色窗帘，床铺上有几何图案被子和一个白色卡通抱枕。整体画面柔和明亮，色调以白色与米色为主，营造出可爱、温暖、甜美的氛围。
```

```json
一位年轻女性斜躺在柔软的床上，穿着白色高领镂空针织毛衣，搭配白色丝袜和蓝色绒面拖鞋。她头戴可爱的羊角发箍，黑色长发扎成双马尾，面带温柔微笑直视镜头。背景是浅色床品与几何图案抱枕，整体氛围温馨、甜美、居家。光线柔和明亮，色调以白色、浅粉和淡蓝为主，画面充满少女感与舒适感。
```    

```json
A young woman lying diagonally on a soft bed, wearing a white high-neck knitted sweater with cut-out details and white thigh-high stockings, paired with light blue fluffy slippers. She has long black hair in twin tails, wearing an adorable sheep-horn headband, smiling gently at the camera. Background includes pastel-colored bedding and geometric patterned pillows. Soft natural lighting, cozy and sweet aesthetic, warm and inviting atmosphere, ultra-detailed skin texture, realistic fabric folds, shallow depth of field, 8K resolution, studio portrait style.
```

```json
一位年轻亚洲女性，留着乌黑柔顺的长发与齐刘海，正温柔微笑看向镜头。她身穿一件白色底、带有浅粉与淡蓝细条纹的吊带背心，领口饰有蕾丝边和一枚粉色小蝴蝶结，下身搭配白色短裤，腿上随意搭着一条浅蓝色破洞牛仔短裤。她坐在室内床上，背景可见绿色棕榈叶图案的窗帘、灰白几何纹靠垫、墙上挂着透明塑料袋装的彩色画笔，以及右侧花卉装饰画框。整体光线柔和明亮，氛围清新自然，构图聚焦人物半身，展现居家休闲感。
```    

```json  
A young Asian woman with long, silky black hair and bangs, gently smiling at the camera. She wears a white spaghetti strap top with delicate pink and light blue horizontal stripes, featuring lace trim and a small pink bow at the neckline. Paired with white shorts, she has a light blue ripped denim short draped over her lap. Sitting on a bed in a cozy indoor setting, background includes a green palm leaf patterned curtain, gray-and-white chevron cushion, wall-mounted clear plastic bag holding colorful paintbrushes, and a floral-framed artwork to the right. Soft natural lighting, warm and inviting atmosphere, medium close-up shot focusing on upper body, capturing casual home aesthetic. Realistic style, high detail, 8K resolution, sharp focus on facial expression and fabric texture.
```

```json
一位年轻亚洲女性在卧室中自拍，她有着柔顺的黑色长发和齐刘海，面带温柔微笑，眼神清澈。她身穿一件浅色条纹吊带睡衣，领口饰有白色蕾丝花边和一个粉色小蝴蝶结，下摆为荷叶边设计。背景是温馨的卧室环境，可见床铺、条纹床单、粉色抱枕及一盏绿色底座的台灯，光线柔和自然。画面构图近景特写，突出人物面部与上半身，整体氛围甜美、清新、居家。
```    

```json
一位20岁左右的亚洲女性，黑长直发带齐刘海，温柔微笑，大眼睛，皮肤白皙细腻，穿着浅粉蓝白条纹蕾丝边吊带睡衣，领口有粉色小蝴蝶结，下摆荷叶边，坐在床上自拍视角，背景是温馨卧室，有条纹床单、粉色花朵抱枕、绿色复古台灯，自然光从侧面照入，画面清晰柔和，甜美清新风格，高细节，8K画质。
```

```json
一位银白色短发、紫唇的性感女性战士，身着华丽的紫色与金色相间的战斗装束，上身为紧身蕾丝胸甲配金属护肩，下身是高开衩蕾丝长裙与绑带式大腿护具，搭配黑色网袜与金属装饰。她双臂交叉于胸前，眼神冷艳自信，背景为阳光明媚的欧洲古典建筑广场（类似威尼斯圣马可钟楼），蓝天白云映衬，画面中漂浮着多个刻有神秘符文的金属立方体，整体风格为超写实动漫风，光影强烈，细节精致，充满戏剧张力与奇幻氛围。艺术家签名“Sakimichan”位于右下角。
```

```json      
A highly detailed, vibrant anime-style illustration of a young woman in a beach volleyball setting. She wears a blue and gold bikini top with crescent moon patterns, paired with a sheer blue sarong tied at her hip. Her skin is glistening with sweat and water droplets, emphasizing a sun-kissed, athletic physique. She holds a white-and-blue volleyball under her left arm, featuring Korean text  "스파이크 " (Spike) on its surface. Her right hand rests on her hip, adorned with a black spiked wristband. Her dark brown hair is tied back with a white ribbon, and she wears red spherical earrings. Behind her, a tropical beach scene unfolds: palm fronds frame the upper left corner, while turquoise ocean waves and a bright blue sky with soft clouds stretch into the background. The lighting is warm and natural, casting soft highlights and shadows to enhance realism and depth. Art style blends dynamic anime proportions with painterly realism, reminiscent of Sakimichan’s signature aesthetic — smooth skin textures, expressive eyes, and fluid fabric movement. Include subtle artist watermark: “ART©SAKIMICHAN.DEVIANTART.COM” and “ART©SAKIMICHAN.TUMBLR.COM” faintly visible in corners. --ar 3:4 --v 6 --q 2 --style raw
```

```json
动漫风格女性角色全身特写，高饱和度光影渲染，柔焦背景中飘散花瓣与朦胧绿植。角色黑长直发随风扬起，头顶架着橙色镜片太阳镜，蓝色眼眸凝视镜头，嘴角微扬带自信神情。身着深蓝露肩短上衣，胸前有白色蝴蝶结装饰与拉链细节，下搭粉色系带腰裙，裙侧饰绿色底白花图案。双手优雅抬起，指尖轻触发丝，姿态动感流畅。整体画面采用霓虹紫粉光晕勾边，皮肤透亮细腻，强调曲线与布料褶皱质感，营造梦幻性感氛围。艺术家签名水印“ART(C)SAKIMICHAN.DEVIANTART.COM”与“ART(C)SAKIMICHAN.TUMBLR.COM”置于画面上下边缘。  
```    

```json    
    动漫风格女性角色，橙红色长发飘逸，棕色眼眸，面带自信微笑。身穿蓝白条纹比基尼上衣，搭配破洞牛仔短裤，腰间系有金属环扣皮带。右手持蓝色圆筒状武器（类似炮管或望远镜），左手轻抚后脑勺，身体前倾呈动态战斗姿势。背景为深色烟雾与飞散金币，带有光影粒子特效，营造动感与戏剧氛围。画面右下角有“ART©SAKIMICHAN.DEVIANTART.COM”水印。整体画风精致细腻，色彩鲜艳，高光与阴影对比强烈，具有插画大师Sakimichan标志性风格。
```

```json
动漫风格女性角色全身特写，粉色渐变长发扎成高马尾，蓝眼睛，佩戴黑色带红色X标志的耳机麦克风。身穿紫色铆钉装饰比基尼上衣与短裤，金色尖刺铆钉点缀，腰间系宽皮带配大型金色兽首扣环。双臂举过头顶，手肘弯曲，姿态性感自信。背景为青蓝色底色+斜向彩虹条纹（粉、黄、蓝、紫），光影柔和带高光渲染，画风细腻带数字绘画笔触感，右下角有“SakiniChun”手写签名水印。整体色彩鲜艳，充满活力与潮流感，突出角色曲线与服饰细节。",
```

```json
A highly detailed, dynamic digital painting of a fierce female warrior in an intense combat pose, holding a katana overhead with both hands, her long dark hair flowing dramatically in the wind. She wears a torn silver-gray tank top revealing toned abs and muscular arms wrapped in white bandages. Her expression is determined and slightly exhausted, with sweat glistening on her skin and dirt smudges across her face. She’s crouched on a dark rock amidst a chaotic battlefield background — glowing embers, blurred trees, and flickering fire at her feet. The lighting is dramatic, with strong backlighting creating rim highlights and volumetric sunbeams piercing through smoke. Art style: hyper-realistic anime-inspired fantasy, rich textures, painterly brushwork, high contrast, cinematic composition. Color palette: warm oranges and yellows from fire, cool greys and blacks on clothing, natural skin tones with wet sheen. Signature watermark “ART(C)SAKIMICHAN.DEVIANTART.COM” faintly visible in corners.
    
    negative prompt:  
    low quality, blurry, cartoonish, flat shading, overly saturated, unrealistic anatomy, extra limbs, deformed face, text overlay, watermark obstructing subject, dull lighting, simple background, anime eyes, chibi, low resolution, noisy, overexposed
    
    --ar 3:4 --v 6 --stylize 750
```

```json
一位年轻亚洲女性，留着乌黑齐刘海及肩发，一侧头发优雅盘起并垂下几缕卷发，佩戴小巧珍珠耳钉。她身穿一件米白色抹胸礼服，胸前有精致刺绣与水晶装饰，外搭轻薄同色系披肩，披肩在胸前打结并自然垂落。她坐在浅灰色皮质沙发中，背景是带有肌理感的米白色墙面，光线柔和明亮，整体氛围温柔、高雅、静谧。镜头为中近景，人物直视镜头，表情平静略带微笑，画面构图平衡，色调温暖柔和。
```


```    一个背对镜头的年轻女性站在阳光明媚的公园小径中央，她留着及腰黑色长直发，身穿白色短袖衬衫和粉色格纹百褶短裙，双手在身后轻轻交握。她穿着带有熊猫头装饰的白色条纹过膝袜和黑色厚底鞋。小径由灰色石板铺成，两旁是茂密的绿树，树叶在阳光下透出明亮的翠绿色，地面上洒满斑驳树影。远处可见中式凉亭、路灯和紫红色灌木丛，天空湛蓝无云。整体画面清新自然，充满青春活力与日系校园风，光线柔和明亮，构图居中，视角略低，突出人物与环境的和谐感。
    
    —
    
    **可选增强指令（如需更高精度）：**
    
    - 画质要求：超高清细节，8K分辨率，真实摄影风格
    - 风格参考：日系少女写真 / 校园风 / 清新自然光摄影
    - 色彩氛围：高饱和度绿色 + 柔和暖阳色调，对比鲜明但不刺眼
    - 人物比例：修长腿部比例，符合亚洲少女审美
    - 环境细节：树影清晰投射在地面，树叶纹理可见，背景有轻微景深虚化
    ```
   
   
```    
    一位年轻、身材匀称的亚洲女性在现代化健身房内使用拉力训练器械。她坐在黑色皮质靠背的健身椅上，身体微微后仰，双手紧握两侧把手，正在进行下拉或划船动作。她留着齐肩中长发，发色为深棕色带浅棕挑染，妆容自然清新，眼神专注略带慵懒地望向镜头右上方。
    
    她身穿一件粉嫩色系的细肩带运动内衣，边缘有白色包边，材质为透气针织面料；下身搭配深灰色高腰运动长裤，裤型修身显腿长，侧边有口袋细节。她的姿势充满力量感与柔美感，腹部线条清晰可见，展现出健康活力的体态。
    
    背景是明亮通透的健身房环境，大面积落地窗引入柔和自然光，窗外绿植虚化形成柔美散景。周围可见其他银灰色金属结构的健身器材，如跑步机、椭圆机等，营造专业而高级的氛围。整体画面色调干净、清新，光线柔和均匀，采用中景构图，焦点精准落在人物面部和上半身，景深适中，突出主体又保留环境质感。
    
    风格：写实、时尚、轻奢健身风，强调光影层次与人物神态表现，适合用于生活方式、运动品牌或社交媒体宣传图。
    
    —
    
    **提示词关键词（可选附加）：**
    
    `realistic, high detail, natural lighting, gym interior, fitness woman, sportswear, pink sports bra, gray leggings, cable machine, soft bokeh, Asian beauty, clean aesthetic, professional photography, shallow depth of field`
    ```
   
   
 ```   
    一位年轻女性在室内镜子前拍摄自拍，采用竖构图、全身视角。她留着深色长发，自然垂落，左手高举过头，轻抚发丝；右手持一部浅灰色 iPhone（后置三摄镜头清晰可见），遮挡部分面部，仅露出下巴与嘴唇轮廓，营造神秘感。她身穿一件简约白色V领短袖上衣，面料轻薄贴身，下搭黑色运动短裤，裤边有白色细条纹装饰。腿上穿着过膝白色薄款丝袜，质感透亮。背景为纯色浅灰或米白墙面，光线柔和均匀，略带生活化氛围。画面右侧及下半部分有轻微动态模糊效果，模拟手持拍摄时的轻微晃动或快门拖影，增强真实感与动感。整体风格清新自然，带有一丝慵懒与私密感。
    
    —
    
    ✅ **适配 Qwen-VL 的优化点：**
    - 明确主体动作与姿态（举手、持机、遮脸）
    - 细节描述到位（手机型号、服装材质、丝袜长度、背景颜色）
    - 加入“动态模糊”、“生活化光线”等视觉特征词，提升真实还原度
    - 风格关键词引导情绪氛围（清新、慵懒、私密）
    ```
 
 
 ```   
  一张高分辨率、电影感十足的自拍风格照片，画面主体是两位年轻女性在电影节红毯上开心合影。
    
    - **人物细节**：
      - 左侧女性：深棕色中长卷发，蓝色眼睛，面带温柔微笑，身穿黑色无袖连衣裙，右手举至胸前比出“V”字胜利手势。
      - 右侧女性：金色波浪长发，绿色眼睛，笑容灿烂露出洁白牙齿，身穿米白色深V领无肩带礼服，左手也比出“V”字手势，与左侧女性形成对称互动。
      - 两人脸庞靠近镜头，呈现自然亲密的自拍视角，眼神直视镜头，充满喜悦与自信。
    
    - **背景环境**：
      - 背景上方是一个醒目的红色横幅，上面用白色粗体无衬线字体写着 “72 FILM FESTIVAL”，数字“72”稍大，整体排版简洁有力。
      - 横幅下方悬挂一串暖黄色小灯泡串，营造温馨梦幻的庆典氛围。
      - 地面铺着鲜红色地毯，远处隐约可见模糊的人群和穿着正装的宾客，增强现场感与纵深感。
    
    - **视觉风格与技术参数**：
      - 整体色调偏暖，略带胶片颗粒质感，模拟35mm胶片摄影效果。
      - 光线柔和自然，来自前方与上方，突出人物面部轮廓与妆容细节。
      - 使用浅景深拍摄手法，使人物清晰锐利，背景适度虚化，聚焦于两位主角的表情与互动。
      - 构图为近景特写，裁剪至胸部以上，强调情感表达与手势符号。
    
    - **情绪与氛围**：
      - 传达欢乐、庆祝、友谊与明星魅力，具有真实活动现场的即兴抓拍感，非摆拍，富有生命力。
    ```
 
 
```    
    > 两位年轻女性在阳光明媚的海滩上开心自拍，镜头视角近似手机前置摄像头，画面充满温暖柔和的胶片感。左边女生留深棕色中长发，穿着鲜艳蓝色短袖T恤，右边女生是金色波浪长发，穿白色吊带背心配浅蓝色牛仔裤。两人并肩微笑，眼睛明亮有神，露出整齐洁白的牙齿，同时用双手比出“V”字胜利手势，手指自然舒展。背景是模糊的沙滩和海面，天空略带灰白但整体光线柔和均匀，营造出夏日午后慵懒又快乐的氛围。照片带有轻微颗粒感、暖色调色偏和边缘柔化效果，模仿35mm胶片相机拍摄风格，构图紧凑，聚焦人物面部表情与互动，传达友谊、自由与青春的美好。
    
    —
    
    **可选增强参数（如支持）：**
    
    - **风格关键词**：胶片摄影 / Kodak Portra 400 / 复古滤镜 / 柔焦效果 / 日系清新
    - **画质要求**：高细节 / 高分辨率 / 自然皮肤纹理 / 真实光影过渡
    - **情绪氛围**：欢快 / 友谊 / 温暖 / 轻松 / 怀旧
    ```


```    
 一张高清晰度、自然光线下的海滩自拍特写照片，画面中两位年轻女性并肩站立，面向镜头，表情夸张有趣，形成鲜明对比。
    
    - **左侧女性：**
      - 深棕色中长直发，自然垂落肩头。
      - 穿着浅蓝色短袖T恤。
      - 表情搞怪：皱眉、眯眼、嘟嘴，做出“生气”或“嫌弃”的鬼脸。
      - 蓝色眼睛，皮肤白皙，面部微带阳光阴影。
    
    - **右侧女性：**
      - 金色长卷发，柔顺披肩。
      - 穿着米白色细肩带吊带上衣。
      - 表情活泼：睁大双眼，张嘴吐出舌头，露出顽皮笑容。
      - 同样蓝眼睛，脸颊泛红，充满青春活力。
    
    - **背景环境：**
      - 典型热带海滩：金黄色细腻沙滩，远处是清澈碧蓝的海水和轻柔翻滚的白色浪花。
      - 天空晴朗无云，阳光温暖明亮，整体色调偏暖，略带胶片质感。
      - 镜头轻微广角畸变，体现手持自拍视角，人物占据画面主要位置，背景略有虚化。
    
    - **风格与氛围：**
      - 自然真实的人像摄影风格，强调生活感、亲密感和幽默感。
      - 两位女性关系亲密，像是闺蜜或姐妹，正在享受度假时光。
      - 整体情绪轻松、俏皮、充满夏日活力。
    ```

```
    一位年轻女性在卧室的全身镜前拍摄自拍。她身穿白色短袖水手领衬衫，搭配深蓝色大蝴蝶结领饰和黑色百褶短裙，呈现日系学生制服风格。她留着齐刘海、中长黑发，右手举着一部银色 iPhone（后置三摄可见），手机屏幕正对镜头，强光反射遮住她的面部，营造出朦胧神秘感。她身体微微前倾，左手自然垂放于大腿旁，姿态略带俏皮。
    
    背景是温馨的日式卧室：左侧是浅木色书架，摆放书籍、相框与悬挂绿植；右侧是一张铺有米白色床单的床，床边有一张木质小书桌，桌上亮着一盏白色弯颈台灯，旁边还有笔筒和文具。墙上贴着几张风景明信片或照片，墙面为暖米色调。整体光线柔和偏黄，氛围安静、私密、生活化，带有胶片感和轻微噪点质感。
    
    构图采用镜面反射视角，人物居中，镜框边缘清晰可见，突出“自拍”主题。请保持真实感、细腻光影与生活气息，避免过度美化或卡通化。
    ```


```    
    一位年轻女性在卧室的全身镜前拍摄自拍。她身穿白色短袖水手领衬衫，搭配深蓝色大蝴蝶结领饰和黑色百褶短裙，呈现日系学生制服风格。她留着齐刘海、中长黑发，右手举着一部银色 iPhone（后置三摄可见），手机屏幕正对镜头，强光反射遮住她的面部，营造出朦胧神秘感。她身体微微前倾，左手自然垂放于大腿旁，姿态略带俏皮。
    
    背景是温馨的日式卧室：左侧是浅木色书架，摆放书籍、相框与悬挂绿植；右侧是一张铺有米白色床单的床，床边有一张木质小书桌，桌上亮着一盏白色弯颈台灯，旁边还有笔筒和文具。墙上贴着几张风景明信片或照片，墙面为暖米色调。整体光线柔和偏黄，氛围安静、私密、生活化，带有胶片感和轻微噪点质感。
    
    构图采用镜面反射视角，人物居中，镜框边缘清晰可见，突出“自拍”主题。请保持真实感、细腻光影与生活气息，避免过度美化或卡通化。
    ```


```    
    这是一张左右拼接的双图照片。
    
    **左图：**
    - 一位金发女性站在不锈钢电梯内，正用手机自拍，手机遮住她的脸。
    - 她身穿黑色挂脖露脐上衣 + 白色羽毛短裙，腰间系着一条棕色皮带。
    - 背景是光滑反光的金属电梯门，左侧墙上有一个绿色按钮的电梯控制面板。
    - 光线明亮，人物姿态自然，氛围现代时尚。
    
    **右图：**
    - 一家充满卡通元素的主题餐厅，墙面上布满蜡笔小新（Crayon Shin-chan）的壁画和装饰。
    - 餐桌为木质长条台，每桌配有嵌入式屏幕、抽油烟机管道（银色波纹管）、烤盘等设备。
    - 椅子是橙色座垫+金属框架，椅背上印有蜡笔小新的图案或文字。
    - 多块彩色电子屏幕播放动画，天花板装有轨道射灯，整体色彩鲜艳、童趣十足。
    - 右下角有水印“知乎 @段老湿”。
    ```

```
    > 一张左右拼接的双图画面。  
    >   
    > **左侧部分：**  
    > 一位年轻金发女性站在不锈钢电梯内，手持黑色智能手机对镜自拍，手机遮挡其面部。她穿着黑色挂脖露脐短上衣，搭配白色羽毛流苏迷你短裙，腰间系棕色皮质腰带。背景为光滑金属质感的电梯门，左侧墙面可见绿色圆形按钮的电梯操作面板。光线明亮均匀，整体风格现代都市时尚。  
    >   
    > **右侧部分：**  
    > 一家以“蜡笔小新”为主题的日式烤肉餐厅内部。墙壁贴满蜡笔小新及其角色的卡通壁画，多块LED屏幕播放动画片段。餐桌为原木长条台，每桌配备嵌入式显示屏、金属波纹排烟管、烤盘和调味罐。座椅为橙色坐垫+银色金属框架折叠椅，椅背印有蜡笔小新图案及中文字样（如“吃货小新”）。天花板装有轨道射灯，地面为浅灰色水磨石纹理。整体氛围活泼、童趣、色彩丰富。  
    >   
    > **构图要求：**  
    > - 左右两图等高并列，中间无明显分割线，保持视觉连贯。  
    > - 左侧人物比例自然，细节清晰（如羽毛裙的层次、金属反光）。  
    > - 右侧餐厅需体现空间纵深感，桌椅排列整齐，灯光与屏幕亮度协调。  
    > - 整体画质高清，色彩饱和度适中，符合真实摄影风格。  
 ```
 
 
```    
    这是一张由三部分组成的拼贴式时尚穿搭展示图：
    
    - **左侧图：** 一位年轻女性在镜子前自拍。她身穿一件紧身黑色高领长袖连体衣，材质半透明带网纱拼接，凸显身材曲线。她的头发盘成高马尾，手持一台复古相机，背景是暖色调的室内墙壁和镜框。
      
    - **中间图：** 一套完整的黑色系时尚单品平铺展示，包括：
      - 一件无袖黑色高领上衣
      - 一条黑色竖条纹阔腿裤
      - 一件饰有白色滚边与流苏的黑色短款外套
      - 一副黑色墨镜
      - 一双黑色尖头高跟鞋（单只）
      - 一双黑色细带高跟凉鞋（成对）
      - 一条银色链式项链
      - 一个黑色翻盖手提包（带有金色“C”形金属扣）
    
    - **右侧图：** 同一位女性穿着中间图中的完整搭配——黑色高领内搭 + 条纹阔腿裤 + 短款外套 + 墨镜架在头顶，手持相机自拍，肩挎黑色手提包，姿态自信优雅，背景为柔和米色纯色墙面。
    
    整组图片风格统一，强调现代都市女性的精致、干练与性感魅力，色彩以黑为主，点缀金色与白色细节，光线柔和均匀。
```


```
    > 请生成一张三联拼贴图，用于展示一位亚洲女性的时尚穿搭。左侧：她在镜前自拍，穿黑色高领紧身连体衣（局部半透明），盘发，手持复古相机，暖光室内背景；中间：平铺展示一套黑色系单品——无袖高领上衣、竖条纹阔腿裤、饰白边流苏的短外套、墨镜、项链、两款高跟鞋、黑色C字扣手提包；右侧：她完整穿着这套搭配，墨镜戴在头上，手持相机，斜挎包，站姿优雅，背景为纯米色墙面。整体风格现代、高级、简约，色调统一为黑色+金色点缀，光线柔和均匀，构图清晰专业。
    
    > **English Prompt:**
    > Generate a triptych collage image showcasing a fashionable Asian woman’s outfit. Left panel: She takes a mirror selfie wearing a black high-neck form-fitting bodysuit with sheer mesh panels, hair in a bun, holding a vintage camera, warm indoor lighting. Middle panel: Flat lay of the full black ensemble — sleeveless high-neck top, vertical-striped wide-leg pants, short jacket with white trim and fringe, sunglasses, silver chain necklace, two pairs of black heels (stiletto and slingback), and a black flap bag with gold “C” clasp. Right panel: She wears the complete outfit, sunglasses perched on head, holding camera, bag slung over shoulder, posing confidently against a plain beige wall. Style: modern, chic, minimalist; color palette: monochrome black with gold accents; lighting: soft and even; composition: clean and professional.
```    


```    
    一位年轻、身材匀称的亚洲女性坐在湖边垂钓。她戴着一顶简约的白色棒球帽，帽檐微微向前，帽子左侧有一个小黑标。她留着乌黑顺直的长发，自然垂在肩后。她身穿一件白色露肩吊带运动背心，搭配黑色长袖防晒袖套和紧身黑色瑜伽裤，露出纤细腰线。脚上穿着一双经典款白色高帮帆布鞋（类似Converse All Star），搭配白色中筒袜，袜口有黑色Nike勾形标志。
    
    她侧身坐在一个白色的塑料折叠箱上，双手握着一根黑色钓鱼竿，正专注地凝视水面，神情宁静而专注。背景是平静的湖面，倒映着岸边模糊的绿树，环境清新自然，光线柔和明亮，呈现出夏日午后户外休闲的氛围。整体画面构图以人物为中心，采用中景视角，突出人物姿态与环境融合的美感，风格写实、干净、时尚。
    
    —
    
    **附加提示词（可选，用于强化细节或风格）：**
    
    - 高清摄影质感，自然光，柔焦背景
    - 服装细节清晰，材质真实（棉质背心、弹力瑜伽裤）
    - 垂钓场景真实，鱼竿与卷线器细节可见
    - 人物表情自然放松，略带沉思
    - 色彩搭配：白+黑为主色调，绿色自然背景衬托
```    


```    
    一位年轻、清秀的亚洲女性，长发自然垂落，身穿米白色短款印花T恤（胸前有花卉图案和英文小字），搭配浅蓝色高腰紧身牛仔裤与白色厚底运动鞋。她站在一棵粗壮古树旁，抬头仰望树枝上悬挂的木质祈福牌（写有文字，系着红色流苏），神情宁静而略带憧憬。
    
    背景是中国传统寺庙庭院：青灰色瓦顶、飞檐翘角、朱红木门与石板地面清晰可见，阳光透过树叶洒下斑驳光影，整体氛围静谧、文艺、充满东方禅意。
    
    构图为中景全身照，人物居画面中央偏左，古树占据右侧，背景虚化突出主体。光线柔和明亮，色调温暖清新，具有高分辨率写实风格，细节丰富（如树皮纹理、衣物褶皱、地面石缝等）。
    
    —
    
    **附加提示词（可选，用于强化效果）：**
    
    - “8K超高清，电影感布光，自然光摄影”
    - “真实皮肤质感，柔焦背景，景深控制精准”
    - “中式庭院美学，祈福文化元素，青春少女感”
```    


```
    一位年轻、清秀的东亚女性，长发飘逸，身穿米色短款印花T恤和浅蓝色高腰紧身牛仔裤，脚踩白色运动鞋，站在一棵挂满木质祈福牌（写有汉字、系着红色流苏）的古老大树下。她微微仰头，目光望向树冠方向，神情宁静而略带向往。
    
    背景是典型的中式庭院：青石铺地，远处可见传统飞檐翘角的古建筑，红柱灰瓦，绿树成荫。阳光明媚，光线从左上方洒落，在地面和人物身上形成柔和自然的光影。整体氛围宁静、治愈、充满东方文化韵味，画面构图采用中景竖版，人物居中偏右，突出人与环境的和谐感。
    
    风格：写实摄影风，高清细节，8K画质，自然光效，色彩清新明亮，强调人物柔美气质与古朴环境的融合。
    
    —
    
    ✅ 此 Prompt 专为 Qwen-VL 设计，包含：
    - 人物特征（外貌、服装、姿态）
    - 环境元素（古树、祈福牌、中式庭院）
    - 光影与氛围描述
    - 构图与风格要求
```    


```    
    一位年轻亚洲女性，约22-25岁，正专注地低头看着笔记本电脑屏幕。她留着柔顺的深棕色中长发，刘海自然垂在额前，戴一副细金属边框的椭圆形眼镜，镜片透明反光。她穿着一件鲜艳的红色吊带内搭，外罩一件宽松的白色针织开衫，衣袖卷至手肘处。脖子上佩戴一颗小巧的珍珠项链，左耳戴着单颗珍珠耳坠。她的表情安静而专注，嘴唇微抿，眼神聚焦于屏幕。背景是明亮的现代办公室环境，浅焦虚化处理，隐约可见后方有两位模糊的女性同事正在工作，窗外透入柔和自然光，整体色调温暖、干净、有电影感。画面构图为近景特写，突出人物面部与上半身，氛围专业又温柔。
    
    —
    
    **提示词增强版（可选）：**
    
    > photorealistic, 8K ultra HD, soft cinematic lighting, shallow depth of field, bokeh background, professional office setting, natural window light, warm color grading, detailed skin texture, realistic hair strands, delicate jewelry, focused expression, Asian beauty, modern minimalist style
```    


```    
    一张由三个垂直拼接的场景组成的时尚生活摄影三联画，整体风格清新、文艺、略带胶片感，色调柔和自然，突出女性优雅与日常氛围。
    
    ---
    
    **左图：窗边休闲少女**
    
    - 一位年轻亚洲女性，留着齐刘海长发，戴着白色头戴式耳机。
    - 她身穿灰色露肩针织上衣 + 白色蓬松短裙 + 灰色运动鞋 + 白色长袜。
    - 姿态：侧身倚靠在复古大窗户边，单腿抬起搭在窗台，手提一个粉色帆布托特包，包上有简约字母印花。
    - 环境：室内走廊，背景是深木门+石砖墙+格子玻璃窗，地面铺有黑白几何图案地砖。
    - 光线：自然光从左侧窗洒入，营造温暖柔和氛围。
    - 风格：街头时尚 + 日常生活感，构图偏中景，人物占画面70%。
    
    ---
    
    **中图：餐厅用餐美人**
    
    - 同一位女性（可微调发型），坐在餐厅餐桌前，直视镜头，表情自然略带慵懒。
    - 穿着浅绿色V领吊带连衣裙，露出锁骨，妆容精致，黑甲油。
    - 手持黑色筷子，面前摆放西餐餐具：白盘、柠檬水杯、小碗酱料、面包、生菜等。
    - 环境：法式或意式餐厅，背景可见其他顾客、百叶窗、墙上挂画、木质门框。
    - 光线：室内暖黄灯光 + 自然光混合，营造温馨高级感。
    - 构图：近景特写，聚焦人物面部与桌面美食，背景虚化。
    
    ---
    
    **右图：街角咖啡馆外**
    
    - 同一女性，换装为白色蕾丝透视吊带长裙，内搭蓝色牛仔裤，手拿棕色麂皮质感小包。
    - 姿态：斜靠在红砖墙边，身体微倾，目光望向镜头，嘴角带笑。
    - 环境：复古咖啡馆外墙，红棕釉面瓷砖+金色花纹装饰，旁边有玻璃窗反射街景，远处可见行人与街灯。
    - 光线：午后阳光斜照，形成柔和阴影，增强立体感。
    - 风格：都市浪漫风，强调建筑纹理与人物柔美对比。
    
    ---
    
    **统一要求：**
    
    - 三幅图人物应为同一人（脸型、五官一致），仅更换服饰与场景。
    - 整体色调保持协调：灰绿、米白、红棕为主，避免高饱和。
    - 拍摄角度真实自然，非过度摆拍，保留生活气息。
    - 画质高清，细节清晰（如布料纹理、指甲油、餐具反光等）。
    - 输出为横向三联画构图，每幅图比例接近1:1，整体宽高比约为3:1。
```    
 
 
```    
    一位优雅的亚洲女性，身着飘逸的橙棕色薄纱长裙，侧卧在浅灰色纹理背景前（类似大理石或水彩晕染效果），姿态慵懒而性感。她黑发微卷，眼神迷离地望向镜头，右手轻抚脸颊，左手自然搭在腰侧，双腿交叠弯曲，脚踝纤细。整体光线柔和偏冷调，突出肌肤质感与纱裙的透明层次。画面右上角有白色艺术字体“影分术 MOVIE HUNTER”，左下角叠加半透明深灰条幅，内有白色简体中文：“直播间里，伊能静贩卖自己”。构图采用横幅电影感比例，氛围兼具时尚大片与私密直播的矛盾感。
```    

```    
    一位年轻、气质优雅的亚洲女性，坐在一张现代风格的金属高脚吧台椅上。她身穿一件修身黑色高领长袖针织衫，搭配一条黑白拼接的A字短裙——裙身外层为光泽感黑色皮质，内衬为纯白色，腰部系着一条宽版黑色皮带，配有银色方形金属扣。她双腿交叠，穿着黑色透明丝袜和尖头黑色漆皮高跟鞋，姿态端庄而自信。
    
    她的长发呈深棕色，自然垂落肩头，妆容精致淡雅，佩戴小巧的珍珠耳钉与一条细链金色吊坠项链。眼神温柔直视镜头，面带浅笑，充满亲和力与知性美。
    
    背景是极简现代风室内空间：墙面与地面均为洁白大理石纹理，左侧有一株高大的绿色龙血树盆栽，增添自然气息；右侧是纯白墙壁，整体光线明亮柔和，营造出干净、高级、时尚的氛围。构图居中，人物占据画面主体，细节清晰，质感细腻，具有商业摄影级别的写实风格。
    
    —
    
    **推荐参数（如支持）：**
    
    - 风格：写实摄影 / 商业人像
    - 光线：柔和自然光 + 室内补光
    - 分辨率：高清 4K 或以上
    - 色调：冷白主调 + 黑白对比 + 绿植点缀
```    


```    
    【画面主体】一位青春可爱的亚洲女学生，身着精致的日式学院风制服，站在室内木质地板上，背景是纯白色墙壁。
    
    【服装细节】
    - 上身：白色短袖衬衫，领口挺括，搭配灰色无袖西装马甲，马甲上有金色纽扣和金色镶边装饰。
    - 领结：黑色大蝴蝶结领带，系在领口中央，略显蓬松。
    - 胸针：左胸佩戴一枚金色徽章，造型类似飞鸟或校徽。
    - 下装：灰色百褶短裙，裙摆边缘有两条平行金色饰边，长度及大腿中部。
    - 鞋袜：黑色中筒袜 + 黑色玛丽珍皮鞋，鞋面有金属搭扣，光泽感强。
    
    【人物姿态与表情】
    - 女孩留深棕色长发，扎成高马尾，用红色缎带束起，发尾自然垂落。
    - 她微微侧身站立，左手轻抚马尾发梢，右手自然下垂微张，姿态活泼俏皮。
    - 面带温柔微笑，眼神清澈明亮，直视镜头，充满亲和力。
    
    【环境与光影】
    - 场景为简约现代室内，纯白墙面 + 人字拼木地板，光线柔和均匀，来自正面偏上方，突出人物立体感与服装质感。
    - 整体色调干净明亮，以灰、白、黑为主，红色发带与金色饰边作为点缀。
    
    【风格要求】
    - 写实风格，高清画质，皮肤细腻有光泽，服装布料纹理清晰可见。
    - 人物比例协调，腿型修长，整体构图居中，全身照，略微仰拍增强视觉冲击力。
```    


```    
    【画面主体】一位青春可爱的亚洲女学生，身着精致的日式学院风制服，站在室内木质地板上，背景是纯白色墙壁。
    
    【服装细节】
    - 上身：白色短袖衬衫，领口挺括，搭配灰色无袖西装马甲，马甲上有金色纽扣和金色镶边装饰。
    - 领结：黑色大蝴蝶结领带，系在领口中央，略显蓬松。
    - 胸针：左胸佩戴一枚金色徽章，造型类似飞鸟或校徽。
    - 下装：灰色百褶短裙，裙摆边缘有两条平行金色饰边，长度及大腿中部。
    - 鞋袜：黑色中筒袜 + 黑色玛丽珍皮鞋，鞋面有金属搭扣，光泽感强。
    
    【人物姿态与表情】
    - 女孩留深棕色长发，扎成高马尾，用红色缎带束起，发尾自然垂落。
    - 她微微侧身站立，左手轻抚马尾发梢，右手自然下垂微张，姿态活泼俏皮。
    - 面带温柔微笑，眼神清澈明亮，直视镜头，充满亲和力。
    
    【环境与光影】
    - 场景为简约现代室内，纯白墙面 + 人字拼木地板，光线柔和均匀，来自正面偏上方，突出人物立体感与服装质感。
    - 整体色调干净明亮，以灰、白、黑为主，红色发带与金色饰边作为点缀。
    
    【风格要求】
    - 写实风格，高清画质，皮肤细腻有光泽，服装布料纹理清晰可见。
    - 人物比例协调，腿型修长，整体构图居中，全身照，略微仰拍增强视觉冲击力。
```    

```
一幅充满都市时尚感的女性肖像图。
    
    **主体人物：**
    - 画面中央是一位年轻的东亚女性，她有着一头柔顺的棕色长卷发，自然地披在肩上。
    - 她的面容精致，皮肤白皙，妆容淡雅，涂着一抹红色的唇膏，眼神温柔而自信地直视镜头。
    - 她的姿态优雅，身体微微侧倾，倚靠在身后的墙壁上，一只手似乎插在裙摆的口袋里，显得轻松而从容。
    
    **服装与细节：**
    - 她身穿一件无袖的浅绿色连衣裙。裙子的设计非常别致：
        - 上半身是修身的褶皱设计，凸显了身材曲线。
        - 下半身是蓬松的百褶短裙，裙摆呈A字形散开，轻盈飘逸。
        - 裙子的下摆边缘有一圈更薄、更透明的同色系纱质面料，增加了层次感和灵动感。
    
    **环境与背景：**
    - 她倚靠在一堵浅灰色的混凝土墙边，墙面质感粗糙，带有细小的斑点，投下了她清晰的影子。
    - 背景是模糊的城市景观，可以看到高楼大厦的轮廓和窗户透出的暖黄色灯光，暗示着拍摄时间可能是黄昏或傍晚。
    - 左下角有一个低矮的混凝土台子，她的一只脚似乎轻轻踩在上面。
    
    **光影与氛围：**
    - 光线来自她的左前方，柔和地照亮了她的脸庞、肩膀和裙装，同时在右侧墙壁上形成了明显的阴影，增强了画面的立体感和戏剧性。
    - 整体色调温暖，浅绿色的裙子与背景中的城市灯光相得益彰，营造出一种宁静、优雅又略带一丝浪漫的都市氛围。
```    
 
 
```    
    一位年轻、清秀的东亚女性，站在纯白色背景前，全身正面中景构图。她拥有乌黑柔顺的长直发，带有自然空气感的齐刘海，发丝微微飘动，增添动感。她的面部轮廓精致，眼神温柔直视镜头，嘴唇微启，表情略带羞涩与自信。
    
    她身穿一件橄榄绿色（军绿/卡其绿）吊带连衣裙：上身为修身紧身设计，细肩带，凸显锁骨线条；下摆为蓬松短裙，腰部有褶皱收腰设计，并装饰有一圈闪亮的银色水钻或珠饰腰链，呈弧形环绕，增加华丽感。
    
    她双手轻抬至胸前，指尖轻轻捏住吊带边缘，姿态优雅而略带俏皮。颈部佩戴一条精致的银色链条项链，镶嵌几何形状的金属装饰和一颗小吊坠，与腰链风格呼应。耳朵上戴着简约圆形耳环。
    
    整体光线明亮柔和，属于专业影棚布光，无明显阴影，突出人物立体感与服装细节。画面干净、时尚、现代，适合用于服装展示或时尚人像摄影。
    
    —
    
    **可选增强指令（如需更高精度）：**
    
    - “高分辨率，8K画质，超写实风格”
    - “皮肤质感细腻光滑，有自然光泽”
    - “服装材质呈现柔软垂坠感，水钻反射高光”
    - “避免任何文字、水印、多余物体”
```    


```    
    一位年轻女性在室内对着镜子自拍。她留着齐刘海的黑色长直发，面部被手机遮挡部分。她身穿一件紧身黑色长袖上衣，凸显身材曲线；下装是黑色高腰短裤，腰部有金属纽扣，两侧大腿处有镂空设计并带有蕾丝花边装饰；搭配黑色过膝长袜，袜口同样饰有蕾丝边。她右手举着一部深绿色手机（类似 iPhone 13 Pro 外观），正在拍摄镜中倒影。背景是一扇浅米色的嵌板式木门，门上有垂直线条和金属拉手。整体光线柔和均匀，画面氛围时尚、性感且略带私密感。
    
    —
    
    **Prompt（英文版，适合国际模型兼容）：**
    
    A young woman is taking a mirror selfie indoors. She has long, straight black hair with bangs; her face is partially obscured by the phone she’s holding. She wears a tight-fitting black long-sleeve top that accentuates her curves, paired with high-waisted black shorts featuring a metal button at the waist and cut-out details on both thighs edged with lace trim. She also wears black thigh-high stockings with lace tops. Her right hand holds a dark green smartphone (resembling an iPhone 13 Pro) up to capture her reflection. The background is a light beige paneled wooden door with vertical grooves and a metallic handle. Lighting is soft and even, creating a stylish, slightly sensual, and intimate atmosphere.
```    

```    
    一位年轻、精致的亚洲女性，拥有乌黑柔顺的齐肩短发，发丝自然垂落，略带蓬松感。她面容清秀，皮肤白皙光滑，妆容精致：深邃的眼线勾勒出明亮大眼，睫毛纤长卷翘，唇色为柔和的珊瑚粉，眼神直视镜头，表情自信而略带一丝冷艳。
    
    她身穿一件纯白色挂脖式露脐上衣，领口设计为高领环形，胸前有金属圆环扣饰，凸显胸部曲线与纤细腰身。下身搭配蓝色高腰牛仔裤，配一条宽版白色皮质腰带，银色金属扣清晰可见。她的左手叉腰，姿态自然放松，右手自然下垂，整体身材比例匀称，腹部平坦紧致。
    
    背景为抽象艺术风格，以深蓝和暗红色为主色调，带有模糊的笔触或布料质感，营造出时尚摄影棚或画廊氛围。光线柔和且富有层次，主要从正面偏上方打光，突出人物面部轮廓与身体线条，阴影过渡自然，整体画面呈现高分辨率、电影级质感，色彩饱和度适中，具有现代时尚杂志封面风格。
    
    —
    
    **建议附加参数（如支持）：**
    
    - 风格：写实摄影风 / 时尚人像 / 高清商业图
    - 分辨率：1080p 或更高
    - 光影：柔和主光 + 环境补光
    - 质感：皮肤细腻、布料纹理清晰、金属反光真实
```    


```    
    一位年轻亚洲女性在户外海边场景中自拍。她留着齐肩的浅棕色或红棕色直发，自然垂落于肩头。她佩戴一副时尚的金色细边飞行员款太阳镜，镜片深黑色，反射出模糊的环境倒影。她的面部表情轻松愉悦，嘴角微微上扬，露出洁白整齐的牙齿，眼神透过墨镜望向镜头。
    
    她身穿一件浅蓝色露肩连衣裙，领口为高领设计，但肩部完全裸露，胸前有褶皱荷叶边装饰，面料轻盈柔软，呈现自然的褶皱感。她的左臂抬起，手肘弯曲，手臂部分进入画面左侧边缘，姿态自然放松。
    
    背景是开阔的海面，海水呈灰蓝色，有轻微波纹；天空多云，光线柔和均匀，整体氛围清新、惬意、度假风。构图为近景特写，聚焦于人物上半身和面部，背景略有虚化以突出主体。
    
    色调偏冷调、干净明亮，具有生活化、真实感的摄影风格，类似手机自拍效果，带轻微噪点与自然光影过渡。
    
    —
    
    **建议附加参数（如支持）：**
    
    - 风格：Realistic / Photorealistic
    - 光线：Soft natural daylight
    - 氛围：Summer vacation, relaxed, stylish
    - 分辨率：High detail, 4K quality
    - 构图：Close-up portrait, slightly tilted angle
```    


```    
    一位优雅迷人的亚洲女性，约30-35岁，留着齐肩黑色直发，带有自然空气刘海，妆容精致：红唇、清晰眼线、柔和高光。她身穿一件深V领黑色丝绒吊带长裙，材质柔滑有光泽，凸显身材曲线。她佩戴一套高级珠宝：一条镶嵌钻石或水晶的Y型流苏项链，一对大尺寸几何造型耳环（银色镶钻），右手无名指戴戒指，左手腕戴简约手链。
    
    她侧身斜靠在米色布艺沙发上，右臂弯曲枕于头后，左手轻放于大腿上，姿态放松而自信，眼神温柔注视镜头，略带微笑。背景是浅木色墙面，墙上挂着三幅现代抽象艺术画作，内容为紫色与灰色调的建筑结构线条（类似桥梁或摩天楼），构图对称。整体光线柔和温暖，来自正面偏左，营造出高端时尚摄影棚氛围。画面色调偏暖，强调质感与奢华感，构图为中景人像，突出人物神态与服装细节。
    
    —
    
    **补充说明（用于增强Qwen-VL理解）：**
    
    - 风格：高端时尚写真 / 精致人像摄影
    - 情绪：优雅、自信、温柔、性感而不俗
    - 关键词：丝绒礼服、珠宝配饰、沙发倚坐、艺术墙画、暖光人像
    - 避免：过度PS感、卡通化、模糊不清、背景杂乱
```    


```    
    一位年轻亚洲女性在圆形化妆镜前用手机自拍。她留着深棕色长发，部分头发扎成高马尾，额前有轻盈的空气刘海，几缕发丝自然垂落在脸颊两侧。她正脸微侧，眼神直视镜头，表情温柔带一丝俏皮，涂着粉红色哑光唇膏。
    
    她身穿一件橄榄绿色罗纹针织长袖上衣，领口为大U型设计，胸前有两个垂直排列的银色金属圆环装饰，形成视觉焦点。脖子上佩戴同色系的细款针织颈圈（Choker），与上衣风格呼应。
    
    她右手举着一部银色 iPhone 13 Pro（或类似型号），手机背面清晰可见三摄镜头模组和苹果Logo，手指修长，指甲修剪整齐并涂有淡粉色指甲油。
    
    背景是纯米色墙面，镜子边缘有明亮的白色LED环形灯带，均匀照亮人物面部与上半身，营造柔和无阴影的影棚级打光效果。画面右上角有“11/16”日期标签和“Orange”字样水印（可选添加）。
    
    整体氛围时尚、精致、生活化，强调服装细节、妆容质感与光影层次，适合用于社交媒体穿搭分享或人像摄影参考。
    
    —
    
    **Prompt（英文增强版，供多语言模型兼容）：**
    
    A young Asian woman taking a mirror selfie in front of a round vanity mirror with bright LED ring light. She has long dark brown hair styled in a messy high ponytail with soft bangs framing her face. Her expression is gentle and slightly playful, looking directly at the camera with pink matte lipstick.
    
    She wears an olive green ribbed knit long-sleeve top with a deep U-neckline and two vertically aligned silver metal O-rings as chest embellishments. A matching thin knitted choker adorns her neck.
    
    In her right hand, she holds a silver iPhone 13 Pro (or similar), clearly showing its triple-camera system and Apple logo. Her nails are neatly manicured with light pink polish.
    
    Background: plain beige wall. The mirror’s white LED ring provides even, shadowless studio lighting on her face and upper body. Optional: add “11/16” date tag and “Orange” watermark in top-right corner.
    
    Style: fashion-forward, lifestyle aesthetic, high detail on fabric texture, makeup, and lighting. Ideal for social media outfit posts or portrait reference.
```    
 
 
```    
    一位年轻东亚女性在机场航站楼内自拍。她留着齐肩黑色直发，自然垂落，面部清秀，眼神直视镜头，表情平静略带自信。她身穿一件纯白色紧身短款T恤，领口为宽U型设计，露出锁骨和部分腹部；下身搭配深色格纹百褶短裙，裙子边缘有白色细线勾勒。她右臂抬起弯曲，手轻抚后脑勺，身体微微前倾，营造出随性又时尚的姿态。
    
    背景是典型的机场环境：左侧可见一排整齐排列的银色金属行李推车，远处有模糊的旅客和柜台，天花板上有嵌入式照明灯和指示牌，整体光线明亮均匀，色调偏冷白。地面为光滑灰色瓷砖，反射出柔和光影。画面构图为中近景特写，聚焦人物上半身与姿态，具有生活感与旅行氛围。
    
    风格要求：写实、高清、自然光效、细节清晰，避免过度修饰或动漫化，保留真实场景质感。
```    


```    
    一位年轻、充满活力的女性站在城市街道的人行道上，面带灿烂微笑直视镜头。她拥有自然蓬松的深棕色长发，略带波浪，随风轻扬。她身穿一件简约修身的白色长袖短款上衣（crop top），露出平坦的小腹；下身搭配一条高腰灰色牛仔百褶迷你裙，裙摆边缘有轻微毛边设计，风格休闲又时尚。脖子上佩戴一条纤细银链，吊坠为小巧的心形。她的姿态自然放松，一只手微微抬起，仿佛正迈步或与人互动。
    
    背景是模糊的城市街景：远处可见绿树、行人轮廓和车辆尾灯形成的柔和光斑（bokeh效果），营造出浅景深摄影氛围。光线为柔和的自然日光，整体色调清新明亮，突出人物主体。画面构图为中景人像，聚焦于人物从头部到大腿中部，强调其青春、自信与都市时尚感。
    
    —
    
    **提示词关键词（可选追加）：**
    
    photorealistic, natural lighting, shallow depth of field, bokeh background, street style, candid moment, smiling woman, urban setting, fashion portrait, high detail, 8K
```    


```    
    一位年轻女性蹲坐在现代都市地铁站或地下通道的地面上，背景是干净整齐的白色瓷砖墙面和灰色防滑地砖。她面向镜头，眼神略带慵懒与酷感，直视观者。
    
    她留着棕色长发，刘海齐眉，戴着一顶黑色蕾丝边贝雷帽，帽子上点缀着小蝴蝶结或金属扣饰。身穿一件简约白色短袖T恤，搭配黑色吊带背心外穿，露出肩部和锁骨；下身穿着黑色条纹过膝长袜和厚底黑色马丁靴，整体风格融合了甜酷与朋克元素。
    
    她的左手手腕佩戴多个黑色皮质手环和金属链条饰品，指甲涂成深色（如黑色或深酒红）。右肩背着一个造型独特的白色毛绒背包——外形像一只趴着的小狗或卡通动物，黑白配色，尾巴蓬松，耳朵竖立，增添可爱反差感。
    
    她呈半蹲姿势，左腿弯曲支撑，右腿屈膝抬起，右手自然搭在膝盖上，身体微微前倾，营造出随性又时尚的街头感。光线柔和均匀，来自上方或前方，没有强烈阴影，突出人物主体与服装细节。整体色调偏冷灰调，但人物肤色温暖，形成视觉对比。
    
    风格要求：写实摄影风，高清晰度，细节丰富，强调服装纹理、饰品光泽与地面反射质感。构图居中偏右，人物占据画面主要位置，背景简洁不喧宾夺主。
```    


```    
    一位年轻优雅的亚洲女性，正脸直视镜头，眼神清澈而略带沉思，表情自然温柔。她拥有精致立体的五官，皮肤白皙细腻，妆容清淡自然，唇色为柔和的珊瑚粉。她的深棕色头发向后梳起，部分发丝轻柔垂落于脸颊两侧，显得随性又不失精致。
    
    她身穿一件纯白色露肩礼服，上衣为宽大的泡泡袖设计，布料柔软有垂坠感，领口呈心形，露出优美的锁骨和肩颈线条；腰部有镂空设计，展现纤细腰身，下装为简约高腰裙摆，整体风格浪漫、高级且现代。
    
    背景是明亮的室内空间，透过大窗户可见模糊的城市高楼轮廓，光线从窗外洒入，营造出柔和的逆光效果，使人物边缘带有轻微光晕。整体色调以白色、浅灰和淡蓝为主，氛围清新、宁静、富有时尚感。
    
    画面构图为中近景特写，焦点集中在人物面部与上半身，背景虚化处理，突出主体。摄影风格为专业人像写真，具有电影感光影与高级质感。
    
    —
    
    **附加建议（用于提升生成质量）：**
    
    - 可添加参数如：“8K超清细节”、“柔焦背景”、“自然光打光”、“时尚杂志封面风格”
    - 若支持负向提示词，可加入：“避免过度磨皮、避免浓妆、避免杂乱背景、避免卡通或插画风格”
```    


    
```    一位年轻、身材匀称的亚洲女性在现代化健身房内进行器械训练。她留着齐肩深棕色直发，皮肤白皙，五官清秀，眼神专注地望向右上方，嘴唇微张，表情自然放松中带有一丝运动时的专注。
    
    她身穿一件浅粉色细肩带运动内衣，边缘有白色包边，材质轻薄贴身；下身搭配深灰色高腰紧身瑜伽裤，凸显腰线和腿部线条。她坐在一台多功能力量训练器械的黑色软垫座椅上，身体微微前倾，右手握住器械的垂直金属拉杆，手臂伸展，正在做拉力训练动作。
    
    背景是典型的健身房环境：银灰色金属器械结构清晰可见，左侧有配重片和调节旋钮，后方玻璃窗透入柔和的自然光，窗外隐约可见模糊的绿植与建筑轮廓，营造出明亮、干净、专业的氛围。整体画面采用中近景构图，焦点集中在人物上半身，景深较浅，背景略微虚化，突出主体。光线柔和均匀，色调偏冷调但肤色温暖，呈现高清写实风格，细节丰富，质感真实。
    
    —
    
    **附加建议（用于提升生成效果）：**
    
    - **模型提示词**：可追加 “highly detailed, realistic photography, professional gym setting, natural lighting, 8K resolution” 等关键词。
    - **避免内容**：请勿添加任何夸张、低俗或不符合健身主题的元素。
    - **风格控制**：若需调整风格，可加入 “cinematic lighting”, “soft bokeh background”, 或 “fitness influencer style”。
```    


```    
    一位年轻女性站在一面装饰华丽的金色雕花边框大镜子前，正在用一部银色 iPhone 自拍。她留着蓬松的棕色长卷发，自然垂落肩头，左手轻轻撩起白色百褶短裙的裙摆，右手举着手机遮住半张脸，只露出部分侧颜和眼睛。
    
    她身穿一件黑色短袖拉链夹克，修身显瘦，拉链从领口一直拉到腰线，胸前有立体口袋设计；下身搭配一条高腰纯白色百褶迷你裙，裙摆呈扇形散开，显得青春活泼。她穿着黑色透明薄款丝袜，脚踩一双黑色漆皮玛丽珍鞋，鞋面带搭扣，厚底设计，增添复古时尚感。
    
    背景是现代简约风格的室内墙面，灰色哑光墙板拼接，嵌有细密的金色竖向金属线条装饰，地面是浅米色抛光大理石瓷砖，边缘有黑色踢脚线。整体光线明亮柔和，人物轮廓清晰，氛围优雅又带点俏皮。
    
    构图为全身镜前自拍视角，画面左右两侧被金色雕花镜框包围，形成视觉框架。请保持真实摄影质感，细节丰富，色彩对比鲜明（黑与白、金与灰），突出服装材质与光影层次。
    
    —
    
    **Prompt（英文精炼版，如需兼容国际模型或双语输入）：**
    
    A young woman takes a mirror selfie in front of an ornate golden-framed full-length mirror. She has long, wavy brown hair and holds a silver iPhone with her right hand, partially covering her face. Her left hand gently lifts the hem of her white pleated mini skirt.
    
    She wears a fitted black short-sleeve zip-up jacket with chest pockets and a white high-waisted pleated mini skirt. She pairs it with sheer black stockings and glossy black Mary Jane shoes with buckles and thick heels.
    
    The background features modern gray wall panels with thin gold vertical lines, and polished beige marble flooring with black baseboards. Lighting is soft and even, highlighting textures and contrasts. The composition is framed by the golden mirror border, capturing a stylish, youthful, and elegant vibe with realistic photographic detail.
```    


```    
    一位年轻的东亚女性正蹲在一面全身镜前，用手机自拍。她留着深色长发，自然垂肩，表情略带慵懒与沉思，眼神直视镜头。她身穿一件纯白色长袖衬衫，领口微开，袖子卷至手肘处；下身搭配一条深灰蓝格纹百褶短裙，裙摆蓬松有层次感；脚穿黑色厚底马丁靴，腿上穿着黑色过膝长袜或打底裤，膝盖部分微微露出。
    
    她右手举着一部浅黄色手机壳的 iPhone（可见三摄镜头），左手自然搭在膝盖上，手腕戴有一只简约银色手镯和一只细金手环。她身体略微侧向镜头，呈半蹲姿势，姿态放松而时尚。
    
    背景是现代简约风格的室内空间：墙面为纯白色，地面是浅灰色瓷砖，右侧门框边缘可见一扇白门，配有黑色长条形门把手，钥匙插在锁孔中。镜子左侧反射出走廊尽头的黑色门框和部分墙壁。整体光线明亮均匀，氛围干净、清新、带点日系少女感，构图采用镜面反射视角，具有真实生活感和自拍氛围。
```    


```    
    A young East Asian woman is crouching in front of a full-length mirror, taking a selfie with her phone. She has long, dark hair falling naturally over her shoulders, and her expression is slightly lazy and contemplative, gazing directly into the camera.
    
    She wears a crisp white long-sleeve shirt with rolled-up sleeves to the elbows, paired with a pleated mini skirt in dark grey-blue plaid pattern. Her legs are covered in black thigh-high socks or tights, with knees slightly exposed. She’s wearing chunky black platform combat boots.
    
    Her right hand holds up an iPhone with a light yellow floral-patterned case (three rear cameras visible), while her left hand rests on her knee. She wears a simple silver bangle and a thin gold bracelet on her left wrist. Her posture is relaxed yet stylish — half-crouched, body angled slightly toward the camera.
    
    The background is minimalist modern interior: white walls, light gray tiled floor. To the right, a white door with a sleek black lever handle is visible, with a key inserted in the lock. The mirror reflects part of a hallway with a black-framed doorway. Lighting is bright and even, creating a clean, fresh, subtly Japanese-style aesthetic. Composition uses mirror reflection perspective for authentic selfie atmosphere.
```    


```    
    一位年轻的东亚女性正蹲在一面全身镜前，用手机自拍。她留着深色长发，自然垂肩，表情略带慵懒与沉思，眼神直视镜头。她身穿一件纯白色长袖衬衫，领口微开，袖子卷至手肘处；下身搭配一条深灰蓝格纹百褶短裙，裙摆蓬松有层次感；脚穿黑色厚底马丁靴，腿上穿着黑色过膝长袜或打底裤，膝盖部分微微露出。
    
    她右手举着一部浅黄色手机壳的 iPhone（可见三摄镜头），左手自然搭在膝盖上，手腕戴有一只简约银色手镯和一只细金手环。她身体略微侧向镜头，呈半蹲姿势，姿态放松而时尚。
    
    背景是现代简约风格的室内空间：墙面为纯白色，地面是浅灰色瓷砖，右侧门框边缘可见一扇白门，配有黑色长条形门把手，钥匙插在锁孔中。镜子左侧反射出走廊尽头的黑色门框和部分墙壁。整体光线明亮均匀，氛围干净、清新、带点日系少女感，构图采用镜面反射视角，具有真实生活感和自拍氛围。
```    

```    
    A young East Asian woman is crouching in front of a full-length mirror, taking a selfie with her phone. She has long, dark hair falling naturally over her shoulders, and her expression is slightly lazy and contemplative, gazing directly into the camera.
    
    She wears a crisp white long-sleeve shirt with rolled-up sleeves to the elbows, paired with a pleated mini skirt in dark grey-blue plaid pattern. Her legs are covered in black thigh-high socks or tights, with knees slightly exposed. She’s wearing chunky black platform combat boots.
    
    Her right hand holds up an iPhone with a light yellow floral-patterned case (three rear cameras visible), while her left hand rests on her knee. She wears a simple silver bangle and a thin gold bracelet on her left wrist. Her posture is relaxed yet stylish — half-crouched, body angled slightly toward the camera.
    
    The background is minimalist modern interior: white walls, light gray tiled floor. To the right, a white door with a sleek black lever handle is visible, with a key inserted in the lock. The mirror reflects part of a hallway with a black-framed doorway. Lighting is bright and even, creating a clean, fresh, subtly Japanese-style aesthetic. Composition uses mirror reflection perspective for authentic selfie atmosphere.
```    

```
    一位年轻、气质冷艳的亚洲女性，拥有浓密柔顺的黑色长卷发，自然垂落肩头。她正对镜头，眼神锐利而自信，妆容精致——强调深邃眼线、自然眉形与裸色唇妆，皮肤白皙无瑕。
    
    她身穿一件设计感极强的黑色西装连衣裙：V型深领口由两片交叉的缎面布料构成，露出锁骨与部分胸部；长袖修身，袖口略微收紧；裙摆为不对称不规则剪裁，前短后长，下摆开衩至大腿中部，展现修长双腿。
    
    她搭配黑色过膝丝袜和吊带袜夹，袜夹从大腿内侧延伸至腰际，增添性感与层次感。右手叉腰，左手自然垂放于身侧，手指涂有亮黑色指甲油，姿态优雅而充满力量感。
    
    背景为纯浅灰色摄影棚背景，光线柔和均匀，采用专业影棚布光，突出人物轮廓与服装质感，整体氛围高级、现代、时尚、略带神秘感。画面构图为中景全身照，人物居中，比例协调，细节清晰。
    
    风格：高分辨率商业时尚摄影，写实主义，强调服装纹理与光影表现。
    
    —
    
    **可选增强词（用于提升生成质量）：**
    
    - “超高清 8K”、“电影级打光”、“皮肤毛孔级细腻”、“丝绸光泽感”、“哑光与缎面材质对比”
    - “情绪：自信、冷静、强大”
    - “避免过度修饰或卡通化，保持真实人体比例”
```    
