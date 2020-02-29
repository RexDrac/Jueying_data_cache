dsr-gait-period: 0.6
epoch-num: 500
epoch-step-num: 5000000
Physics-frequency: 1000
tau: 0.001
loss-output-smooth-coeff: 1.0
controlled-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
actor-l2-reg: 0.0003
actor-action-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
imitation-weight: 0.5
filter-torque: False
loss-output-diff-coeff: 0
test-num: 4
max-path-step: 5000
loss-entropy-coeff: 0.0
actor-logstd-bounds: [[-1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791
  -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791]
 [-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
gamma: 0.986
actor-output-bounds: [[-1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1.]
 [ 1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.]]
max-path-num: 20
critic-l2-reg: 0.0003
task-weight: 0.5
prioritized-exp-replay: True
actor-activation-fn: ['relu', 'relu', 'None']
reward-scale: 0.1
joint-interpolation: True
max-train-time: 10
n-step: 1
state-dim: 25
batch-size: 128
train-step-num: 1
max-step-num: 2500000000
gating-index: [0, 1, 2, 3, 4, 5, 6, 7, 8, 11, 12]
render-eval: False
max-test-time: 10
critic-activation-fn: ['relu', 'relu', 'None']
total-step-num: 2500000000
critic-weight-decay: 1e-06
actor-weight-decay: 1e-06
env-id: HumanoidBalanceFilter-v0
HLC-frequency: 25
actor-layer-size: [256, 256]
replay-ratio: 1
dsr-gait-freq: 1.667
rollout-step-num: 1
squash-action: True
replay-buffer-size: 1000000
loss-output-bound-coeff: 0.0
LLC-frequency: 500
gating-layer-size: [128, 128]
critic-layer-size: [256, 256]
actor-logstd-initial: [[-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
action-dim: 12
max-episode-num: 5000000
expert-index: [0, 1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 13, 14, 15, 16, 17, 18, 19, 20, 21, 22, 23, 24]
actor-lr: 0.0003
replay-start-size: 10000
bullet-default-PD: False
interpolation: False
critic-lr: 0.0003
action-bounds: [[-0.5236 -2.7925  0.6981 -0.5236 -2.7925  0.6981 -0.5236 -2.7925  0.6981
  -0.5236 -2.7925  0.6981]
 [ 0.5236  0.3491  2.7925  0.5236  0.3491  2.7925  0.5236  0.3491  2.7925
   0.5236  0.3491  2.7925]]
expert-num: 8
normalized-action-bounds: [[0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]
 [0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]]
categorical-distribution: {'v_max': 250, 'n_atoms': 51, 'v_min': -10}
record-start-size: 10000.0
filter-action: True
gating-activation-fn: ['tanh', 'tanh', 'None']
