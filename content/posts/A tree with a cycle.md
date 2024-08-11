---
title: "A tree with a cycle"
date: 2024-08-11T22:35:00+09:00
draft: false
tags: ["tree", "cycle", "geneology"]
categories: ["academia"]
---

주변 지인들은 나한테 들어서 아는 이야기일 수 있지만, 기록해둔다는 생각으로 오랫만에 포스트를 더해본다 (앞으로는 더 자주 써야겠다). 

Academic Geneology, 그러니까 학계 가계도는 박사과정 지도교수를 parent node로, 지도학생을 child node로 삼아 연결해 만드는 tree이다. 물론 2~3세대를 넘어가면 서로 함께 활동할 확률이 낮아지니까, 이걸로 "뿌리"를 논하는 게 큰 의미는 없는 가계도이기는 하다. 하지만 자기 가계도를 쭉 따라 올라가면 [오일러](https://www.mathgenealogy.org/id.php?id=38586)나 [가우스](https://www.mathgenealogy.org/id.php?id=18231)가 등장한다면 또 나름 재미있는 일이기도 할 것이다. 나는 가계도가 오일러에 닿는 주변 교수님을 적어도 한 분 알고 있다 :)

정의상 통상적인(...) 가계도는 tree이고, tree의 정의는 root node를 제외하고는 모든 노드가 한 대의 edge의 타겟이 되는 acyclic 그래프이다. 오늘 하려는 이야기는, 내 학계 가계도는 tree가 아니라는 이상한(?) 이야기이다. 중간에 cycle이 있기 때문이다. 좀 이상한 이야기지만, 지도교수님인 Prof. Mark Harman 교수님께 물려 받은 수없이 많은 소중한 것들 중에서, 나는 가계도가 가지는 이 이상한 수학적 성질을 특히 소중히 생각하는 편이다. 

내 지도교수님은 스스로 종종 말씀하셨듯이 working class 출신인데 (요즘엔 건강을 생각해서 그만두신 것 같지만, 가끔 본인 출신의 증거라며 "[greasy spoon](https://en.wikipedia.org/wiki/Greasy_spoon)" 까페에 가자고 하시던 적이 있었다), 성적이 뛰어났기 때문이었겠지만 석사과정은 Imperial College에서 마쳤다. Imperial은 엄청난 명문 학교이지만 동시에 런던에서도 가장 부유한 동네에 자리잡은 학교이고, 모르긴 해도 당시 그곳의 학풍과 분위기는 고고하고 조금 콧대높은, 그런 것이었나보다. 석사를 마친 지도교수님은 박사과정에 진학하겠다고 결심했는데, 대신 지금까지 내가 배운 걸 Imperial보다 더 못한 환경에 있는 사람들에게 돌려줄 필요도 있다는 생각에, 한국으로 치면 전문대학교나 직업학교에 더 가까운 Polytechnic of North London으로 1988년에 진학을 했다. 문제는 당시 Polytechnic of North London 강사진 중에는 박사학위 소지자가 없었다는 점이다. 어떤 논의가 오갔는지 자세한 이야기는 듣지 못했지만, 결국 당시 Polytechnic of Noth London에 재직중이던 [Sebastian Danicic](http://sebastian.doc.gold.ac.uk) 교수님이 지도교수를 맡았고, 필요한 경우 공동지도를 받았다고 들었던 것 같다. 지도교수님은 92년에 박사학위를 마쳤는데, 1992년은 영국 고등교육법 개정으로 Polytechnic University들이 모두 정식 대학으로 승격된 해이다. 결국 자기가 박사학위를 딴 학교에서 바로 임용이 되어서, 1997년에는 학과장까지 승진한다. 그 뒤로 Goldsmith, Brunel을 거쳐서 2004년에 King's College London으로 자리를 옮겼고, 내가 King's 석사과정에 입학한 것은 2005년 가을이다.

여기서 끝나면 딱히 재미있는 이야기도 아니고, 가계도가 꼬일 이유도 없다. 이 이야기의 가장 흥미진진한 부분운, Sebastial Danicic 교수님이 본인도 박사학위를 따겠다고 결심했고, 1999년에 학위를 마쳤다는 점이다. 지도교수가 누구냐면... Mark Harman 교수님, 내 지도교수님이다. 그러니까 학계 가계도상 내 할아버지는 동시에 내 sibling이다 :) Danicic 교수님이 무슨 명예 박사학위같은 걸 제자를 통해 쉽게 딴 거라면, 당연히 이 이야기는 남들에게 자랑스럽게 들려줄 게 못 되었을 것이다. 내 지도교수님의 박사학위 논문 제목은 Functional Models of Procedural Programs이고, Danicic 교수님의 박사학위 논문 제목은 Dataflow Minimal Slicing이다. Harman 교수님은 좀 더 넓은 functional model에서 시작해 결국 program slicing에서 경력 초반 연구의 본령을 맞았고, Danicic 교수님은 같은 분야에 투신해서 [중요한 논문을 여러 편](https://scholar.google.com/citations?user=5n-OpAEAAAAJ&hl=en) 함께 쓰셨다.

본인이 Polytechnic of North London으로 옮겨간 이야기를 해주실 때면, 지도교수님은 버나드 쇼가 했다는 "20대에 공산주의자가 아니면 가슴이 없는 사람이고, 30대에 자본주의자가 아니면 머리가 없는 사람이다"라는 말을 덧붙이며 과거의 자기 자신이 내린 결정이 사뭇 어이없다는 듯한 표정을 짓곤 하셨다. 하지만 나는 무모하다시피 한 내 지도교수님의 박사학위, 그리고 자기 제자에게 지도를 받기로 한 Danicic 교수님의 박사학위 모두 좋아하고, 훌륭한 일화라고 생각한다. 덕분에 내 학생들은 모두 이 이상한 가계도를 물려받게 되었는데, 나처럼 이 이상한 그래프를 자랑스럽게(?) 생각해줬으면 하는 바램이 있다.