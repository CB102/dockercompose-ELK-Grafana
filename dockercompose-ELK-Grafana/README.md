1. (centos7) sudo yum -y update 
- sudo yum install -y curl ssh git
- curl -sSL https://get.docker.com | sh
- sudo curl -L "https://github.com/docker/compose/releases/download/1.22.0/docker-compose-$(uname -s)-$(uname -m)" -o /usr/local/bin/docker-compose

2. check docker work or not

3. systemctl start docker
如果要設定 Docker 在開機時自動啟動：
sudo systemctl enable docker  # 啟動 Docker 服務
sudo systemctl disable docker # 關閉 Docker 服務

4. 文件挂载
sudo sysctl -w vm.max_map_count=262144

5. vi your docker-compose  &  docker-compose up 
