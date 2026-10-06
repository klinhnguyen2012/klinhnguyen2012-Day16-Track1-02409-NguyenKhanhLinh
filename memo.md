# Memo Teardown — ChatGPT

**Họ tên:** [Điền họ tên]

**Vì sao chọn sản phẩm này:** ChatGPT là sản phẩm AI-native, trong đó AI là toàn bộ trải nghiệm chứ không phải một lớp tính năng. Sản phẩm có lịch sử công khai dày, nhiều lần đổi use case rõ ràng và đủ nguồn gốc để dựng timeline từ research preview đến search, research và agent.

## §1. Timeline các cập nhật lớn

| Thời điểm | Cập nhật | Context lúc đó | Nguyên lý |
|---|---|---|---|
| **30/11/2022** | ChatGPT ra mắt dưới dạng **research preview**, miễn phí, dựa trên GPT‑3.5. [Nguồn OpenAI](https://openai.com/index/chatgpt/) · [Product Hunt](https://www.producthunt.com/products/chatgpt) | OpenAI vẫn tự định vị là lab nghiên cứu và chưa biết nhu cầu consumer thực tế đến đâu. Launch nhỏ giúp họ lấy phản hồi thật thay vì chờ sản phẩm hoàn hảo. | **Vòng lặp học — Iterative deployment:** tung sớm để quan sát hành vi, lỗi và use case rồi cải tiến. |
| **14/03/2023** | GPT‑4 được đưa vào ChatGPT Plus; bắt đầu có tầng trả phí với model mạnh hơn. [Nguồn GPT‑4](https://openai.com/index/gpt-4/) · [Release Notes](https://help.openai.com/en/articles/6825453-chatgpt-release-notes) | ChatGPT đã chứng minh nhu cầu lớn; Microsoft tích hợp công nghệ OpenAI vào Bing/Edge và Google chuẩn bị Bard. OpenAI cần vừa nâng năng lực vừa tạo doanh thu để chi trả compute. | **X10:** nâng chất lượng đủ lớn để người dùng giao nhiệm vụ khó hơn, đồng thời biến giá trị đó thành subscription. |
| **23/03/2023** | ChatGPT plugins, browsing và code interpreter bắt đầu được thử nghiệm. [Nguồn OpenAI](https://openai.com/index/chatgpt-plugins/) | Model có giới hạn: kiến thức cũ, không truy cập dữ liệu riêng, chỉ sinh text và dễ hallucinate. OpenAI bắt đầu kết nối ChatGPT với web, Python và dịch vụ bên thứ ba. | **Wrapper/moat:** giá trị không chỉ nằm trong model; tools, workflow, dữ liệu và hành động bên ngoài tạo ra lớp khó thay thế hơn model thuần túy. |
| **06/11/2023** | Ra mắt GPTs: người dùng tạo phiên bản ChatGPT chuyên biệt mà không cần code. [Nguồn OpenAI](https://openai.com/index/introducing-gpts/) · [AP context](https://apnews.com/article/da850be425aaa269e2915e9e0b1c726a) | ChatGPT đã đạt quy mô rất lớn; tại DevDay, OpenAI nói sản phẩm có hơn 100 triệu weekly active users và 2 triệu developers. Bard và Claude đã xuất hiện, nên OpenAI cần mở rộng hệ sinh thái thay vì chỉ cạnh tranh bằng model. | **Vertical AI:** biến model tổng quát thành nhiều trợ lý chuyên biệt theo từng nhiệm vụ, ngành và workflow. |
| **10/01/2024** | GPT Store và ChatGPT Team được ra mắt. [GPT Store](https://openai.com/index/introducing-the-gpt-store/) · [ChatGPT Team](https://openai.com/index/introducing-chatgpt-team/) | Sau GPTs, người dùng đã tạo hàng triệu phiên bản tùy biến. OpenAI thử hai hướng: marketplace/community ở consumer và workspace an toàn ở team/doanh nghiệp. | **Network effect / wrapper-moat:** càng nhiều builder tạo GPT, càng nhiều use case, nội dung và discovery trong hệ sinh thái. |
| **13/05/2024** | GPT‑4o đưa text, audio và vision vào một model; nhiều công cụ được mở rộng cho người dùng miễn phí. [Nguồn OpenAI](https://openai.com/index/hello-gpt-4o/) | ChatGPT đã trở thành sản phẩm đại chúng. Cạnh tranh chuyển từ “ai có chatbot” sang “ai tạo được trợ lý tự nhiên, nhanh và đa phương thức hơn”. | **Định nghĩa “tốt”:** chất lượng không chỉ là câu trả lời đúng; còn là độ trễ, tính tự nhiên, khả năng nhìn/nghe và mức độ dễ tiếp cận. |
| **31/10/2024** | ChatGPT Search cho câu trả lời cập nhật kèm link web. [Nguồn OpenAI](https://openai.com/index/introducing-chatgpt-search/) | ChatGPT bị giới hạn bởi dữ liệu huấn luyện; Google, Bing và Perplexity cạnh tranh ở lớp search/answer engine. OpenAI dùng phản hồi từ prototype SearchGPT để đưa search vào sản phẩm chính. | **Định nghĩa “tốt” + wrapper/moat:** câu trả lời tốt phải kịp thời, có nguồn và kiểm chứng được; lợi thế là kết hợp hội thoại với retrieval. |
| **02/02/2025** | Deep Research trở thành agent có thể tự lập kế hoạch, duyệt web, phân tích nhiều nguồn và viết báo cáo. [Nguồn OpenAI](https://openai.com/index/introducing-deep-research/) | Năng lực reasoning và browsing đã đủ để xử lý tác vụ dài hơn một lượt chat. OpenAI chuyển từ “AI trả lời” sang “AI làm knowledge work” cho finance, science, policy và engineering. | **Agentic Vertical AI:** AI thực hiện trọn workflow chuyên môn nhiều bước và tạo ra work product có thể dùng được. |

**Vì sao chọn những mốc này:** Các mốc này đại diện cho những quyết định làm thay đổi người dùng, năng lực hoặc định vị của ChatGPT: launch, pricing, tools, customization, ecosystem, multimodality, search và agent. Tôi loại iOS vì đây chủ yếu là mở rộng distribution; loại Memory vì là lớp personalization; loại DALL·E 3 vì GPT‑4o bao quát hơn; và loại các bản vá/model nhỏ vì không đủ tư cách là pivot sản phẩm.

## §2. Tệp user & JTBD

| | Early adopters | Tệp hiện tại |
|---|---|---|
| **Đặc điểm** | Một frontend developer 25–35 tuổi ở startup nhỏ, dùng VS Code/GitHub, theo dõi AI trên Twitter/Hacker News/Product Hunt và sẵn sàng thử tool chưa hoàn thiện. Họ dùng ChatGPT để debug, giải thích API, viết script, brainstorm và kiểm tra giới hạn model. Các bài viết/launch thời kỳ đầu cho thấy người dùng cũng thử viết lại văn bản, làm bài tập và kiểm tra code. [Product Hunt newsletter](https://www.producthunt.com/newsletters/archive/16758-why-chatgpt-is-blowing-up-the-web) · [TIME](https://time.com/6253615/chatgpt-fastest-growing/) | Một knowledge worker, sinh viên hoặc người dùng phổ thông có smartphone, email và tài liệu số nhưng không nhất thiết biết code. Họ mở ChatGPT để viết/chỉnh email, tóm tắt, học, lập kế hoạch, hỏi thông tin, dịch, brainstorm hoặc hỗ trợ quyết định. Nghiên cứu usage của OpenAI cho thấy phần lớn hội thoại tập trung vào practical guidance, information-seeking và writing. [OpenAI usage study](https://openai.com/index/how-people-are-using-chatgpt/) · [Harvard Kennedy School summary](https://www.hks.harvard.edu/publications/how-people-use-chatgpt) |
| **JTBD chính** | “Khi tôi bị kẹt trong một vấn đề kỹ thuật hoặc ý tưởng chưa rõ, tôi muốn có một người cộng tác phản hồi ngay để thử nhiều hướng và tạo prototype nhanh, để tôi ship hoặc học nhanh hơn mà chưa cần nhờ thêm chuyên gia.” | “Khi tôi gặp một nhiệm vụ trí óc hoặc giao tiếp lặp lại, tôi muốn nói yêu cầu bằng ngôn ngữ tự nhiên và nhận một bản nháp/giải thích/kế hoạch có thể chỉnh sửa, để hoàn thành việc nhanh hơn và bớt ma sát từ trang trắng hoặc việc mở quá nhiều nguồn.” |
| **Trước đó họ làm bằng cách nào** | Google, Stack Overflow, documentation, GitHub issues, hỏi đồng nghiệp, tự viết thử và ghép nhiều tool rời rạc. Họ chấp nhận quy trình này vì cần kiểm chứng kỹ thuật, nhưng mất nhiều thời gian chuyển context. | Tự viết từ đầu, tìm kiếm web, dùng template, hỏi đồng nghiệp/giảng viên, ghi chú thủ công hoặc chuyển qua nhiều app. ChatGPT không thay thế hoàn toàn phán đoán; nó rút ngắn bước khởi động và tổng hợp. |

**Dịch chuyển tệp:** Ban đầu sản phẩm hút nhóm AI-curious power users vì họ chịu được lỗi và muốn khám phá capability mới. Các mốc **GPT‑4/Plus** mở rộng chất lượng cho nhiệm vụ nghiêm túc; **iOS** đưa sản phẩm vào thói quen hàng ngày; **GPT‑4o** làm voice/vision nhanh và dễ tiếp cận hơn. Từ đó, user không còn chỉ là developer hoặc hobbyist mà gồm cả người viết, sinh viên, nhân viên văn phòng và người dùng cá nhân. Usage study gần đây cũng cho thấy non-work use và practical guidance chiếm phần lớn hành vi hiện tại.

**Switching cost — map 4 forces:**

| Force | Cách nó hoạt động với ChatGPT |
|---|---|
| **Push — lực đẩy khỏi cách cũ** | Trang trắng, email/tài liệu lặp lại, tìm kiếm nhiều tab, context bị phân mảnh và áp lực phải hoàn thành nhanh. Với knowledge work, đây là lực đẩy lớn nhất để bắt đầu dùng. |
| **Pull — lực hút sang ChatGPT** | ChatGPT kết hợp độ rộng use case, giao diện hội thoại, file/image/voice, Search, Memory và Deep Research. Người dùng có thể bắt đầu bằng yêu cầu mơ hồ rồi cùng AI làm rõ. |
| **Anxiety — lo lắng khi chuyển sang** | Hallucination, giọng văn generic, privacy, giới hạn message, sợ phụ thuộc AI và lo output không đáng tin. Đây là lý do user vẫn kiểm chứng hoặc dùng song song Claude, Gemini, Perplexity và Google. |
| **Habit/inertia — thói quen/quán tính** | App đã nằm trong browser/điện thoại; lịch sử chat, custom GPTs, file, prompt quen thuộc và workflow cá nhân khiến việc mở ChatGPT trở thành phản xạ. Tuy nhiên switching cost dữ liệu chưa thật sự cao vì user có thể multi-home. |

**Lực giữ user mạnh nhất:** hiện tại là **Pull được củng cố bởi Habit** — ChatGPT là lựa chọn mặc định đủ rộng cho nhiều việc và đã trở thành thói quen. Nếu mất lợi thế “default general assistant” đó, user có thể chuyển khá nhanh sang Claude/Gemini/Perplexity vì ChatGPT chưa khóa chặt dữ liệu hay workflow đến mức không thể rời đi.

## §3. Ba dự đoán hướng đi (6–12 tháng tới)

**Dự đoán 1** *(loại: mở rộng tính năng)*

- **Dự đoán:** ChatGPT sẽ đẩy mạnh các agent chạy dài, có lịch, có approval và kết nối trực tiếp với email, drive, calendar, CRM, Slack/GitHub; chat sẽ dần trở thành nơi giao mục tiêu thay vì nơi nhận từng câu trả lời.
- **Lập luận:** Timeline đã đi từ plugins → Search → Deep Research → agent. Các cập nhật Workspace Agents và ChatGPT Work hiện cũng nhấn mạnh shared context, connected tools, scheduled work và long-running workflows. [Workspace Agents](https://openai.com/index/introducing-workspace-agents-in-chatgpt/) · [ChatGPT Work](https://openai.com/index/chatgpt-for-your-most-ambitious-work/)

**Dự đoán 2** *(loại: mở rộng segment)*

- **Dự đoán:** Tệp tăng trưởng quan trọng nhất sẽ là team nhỏ, SMB và các bộ phận vận hành — sales, support, marketing, finance — dùng shared agents thay vì mỗi cá nhân tự chat.
- **Lập luận:** GPTs/Team đã mở hướng doanh nghiệp, còn Workspace Agents chuyển nó thành workflow chung có quyền, memory và tool access. Điều này nối trực tiếp với JTBD hiện tại: biến việc viết, tổng hợp, follow-up và báo cáo lặp lại thành quy trình có thể giao cho agent. [Workspace Agents](https://openai.com/index/introducing-workspace-agents-in-chatgpt/)

**Dự đoán 3** *(loại: thay đổi mô hình kiếm tiền)*

- **Dự đoán:** Pricing sẽ tách rõ “chat cơ bản theo seat” khỏi “agent execution theo credits/usage”, kèm các gói enterprise có governance, connectors và ngân sách compute riêng.
- **Lập luận:** ChatGPT đã đi từ free preview → Plus → Team/Enterprise; các agent mới cần compute và chạy dài nên khó giữ mô hình subscription phẳng. Việc OpenAI đã dùng credit-based pricing cho workspace agents và phát triển Ads Manager cho thấy monetization đang mở rộng ngoài subscription đơn giản. [Workspace Agents](https://openai.com/index/introducing-workspace-agents-in-chatgpt/) · [ChatGPT ads](https://openai.com/index/new-ways-to-buy-chatgpt-ads/)

**Dự đoán tự tin nhất:** Dự đoán 1, vì nó là bước nối trực tiếp nhất từ Deep Research/agent và đã có tín hiệu sản phẩm rõ. Giả định có thể làm nó gãy là **agent chưa đủ đáng tin để được giao quyền tự động trên dữ liệu và workflow quan trọng**; nếu approval, privacy và reliability không đạt, user sẽ quay lại dùng ChatGPT như copilot thủ công.

## §4. AI Log

| Việc | AI làm hay bạn làm? | Bạn kiểm chứng/phán đoán lại thế nào? |
|---|---|---|
| Tìm và tổng hợp changelog, Product Hunt, founder interview và usage research | **AI hỗ trợ tìm kiếm/tổng hợp** | Mở lại các link gốc của OpenAI, Product Hunt, Apple Podcasts, AP, TIME và Harvard; không dùng search snippet làm nguồn cuối. |
| Chọn 8 cột mốc từ 16 mốc ứng viên | **AI đề xuất bộ lọc; người làm bài phán đoán** | Giữ các mốc làm đổi product decision, segment, pricing hoặc JTBD; loại iOS, Memory, DALL·E 3 và các update nhỏ vì không đủ lớn. |
| Revert mỗi mốc về nguyên lý x10, wrapper/moat, Vertical AI, learning loop và definition of good | **AI hỗ trợ diễn giải; người làm bài chịu trách nhiệm lập luận** | Kiểm tra mỗi nhãn có giải thích được bằng “quyết định này tạo leverage gì?”; loại các nhãn chung chung như “để tăng trưởng”. |
| Xác định early adopters và tệp hiện tại | **AI tổng hợp bằng chứng; người làm bài phán đoán segment** | Đối chiếu review/usage study với mốc GPT‑4, mobile và GPT‑4o; viết persona cụ thể thay vì gọi chung là “developer” hoặc “mọi người”. |
| Phân tích JTBD và 4 forces | **Người làm bài phán đoán, AI hỗ trợ cấu trúc** | Viết theo công việc cần hoàn thành và cách cũ; kiểm tra riêng push, pull, anxiety và habit/inertia; kết luận switching cost chưa cao. |
| Viết 3 dự đoán 6–12 tháng | **AI tạo bản nháp; người làm bài chịu trách nhiệm nhận định** | Mỗi dự đoán phải nối với ít nhất một mốc timeline và một nhận định về user; đối chiếu thêm Workspace Agents, ChatGPT Work và monetization updates. |
| Kiểm tra dữ kiện ngày tháng | **AI hỗ trợ kiểm tra** | Đã sửa ngày Deep Research từ 21/02/2025 thành **02/02/2025** theo trang OpenAI chính thức. |

