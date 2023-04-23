svgframes = states_frames

media: trotsky
frames: media title discussion1 discussion2 discussion3 discussion4 discussion-full

trotsky:
	cp ../challenge_23-04-08/"A x Leon-Trotsky-Russian-Communist-leader.jpg" ./"A x trotsky.jpg"

title:
	inkscape --export-filename="title_card.png" --export-id="title-bg" \
	--export-type="png" $(svgframes).svg
discussion1:
	inkscape --export-filename="D28b1 discussion.png" --export-id="discussion1-bg" \
	--export-type="png" $(svgframes).svg
discussion2:
	inkscape --export-filename="D28b2 discussion.png" --export-id="discussion2-bg" \
	--export-type="png" $(svgframes).svg
discussion3:
	inkscape --export-filename="D28b3 discussion.png" --export-id="discussion3-bg" \
	--export-type="png" $(svgframes).svg
discussion4:
	inkscape --export-filename="D28b4 discussion.png" --export-id="discussion4-bg" \
	--export-type="png" $(svgframes).svg
discussion-full:
	inkscape --export-filename="D28b discussion.png" --export-id="discussion-bg" \
	--export-type="png" $(svgframes).svg

clean:
	rm "A x trotsky.jpg" \
	"title_card.png" "D28b1 discussion.png" "D28b2 discussion.png" "D28b3 discussion.png" "D28b4 discussion.png" "D28b discussion.png"
