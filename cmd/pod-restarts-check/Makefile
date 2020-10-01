IMAGE="kuberhealthy/pod-restarts-check"
TAG="v2.3.1"

build:
	docker build -t ${IMAGE}:${TAG} -f Dockerfile ../../

push:
	docker push ${IMAGE}:${TAG}
